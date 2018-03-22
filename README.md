Add a shell-script wrapper to call busybox

usage: 
## Container:

```
 ./busybox ls -al    #performs a ls -al using the busybox binaries
```

## Raw

```
wget https://raw.githubusercontent.com/akbennett/busybox-wrapper/master/busybox -O busybox
chmod +x busybox
alias busybox=$PWD/busybox

busybox ls -al        #performs a ls -al using the busybox binaries
busybox vi README.md  #open Readme with busybox vi
```

## Git

```
wget https://raw.githubusercontent.com/akbennett/busybox-wrapper/master/git -O git
chmod +x git
alias git=$PWD/git

git status       #git status 
```
