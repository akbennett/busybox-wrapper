# Utilities

A collection of scripts that can be ran on a system that runs docker, but 
does not have local utilities

## Pull down the scripts and create an alias

```
wget https://raw.githubusercontent.com/akbennett/utilities/master/busybox -O busybox
chmod +x busybox
alias busybox=${PWD}/busybox
alias vi='$PWD/busybox vi'
alias ls='$PWD/busybox ls'
wget https://raw.githubusercontent.com/akbennett/utilities/master/git -O git
chmod +x git
alias git=$PWD/git
```

## Samples invocations 
```
busybox ls -al   # performs a ls -al using the busybox binaries
vi README.md     # open Readme with busybox vi
git status       # git status 
```
