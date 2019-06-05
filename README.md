### Jenkinsfile

# Basic Jenkinsfile to get initial pipeline working with either gitlab or github as well as jenkins

## Note: These for these to work as is, you will need to have jenkins running as a service, on either your windows or nix slave node. You will also want the BlueOcean as well as the git and github plugins on your jenkins server. 

To use, drop either jenkinsfile in your git repo. The windows version utilizes powershell and the nix/mac is pure sh.

## To set up in jenkins do the following. 

1. On your BlueOcean Dashboard click "create new pipeline project" (These are declaratice jenkinsfiles and it will create a multibranch pipeline by default)
2. Choose github or git
3. Add the jenkins servers ssh key to your git account if you haven't already.
4. Push changes to your branches
5. Profit. 
