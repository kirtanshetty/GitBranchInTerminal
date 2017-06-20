# GitBranchInTerminal
Show git branch on your terminal

Clone and add this file in your home directory with 755 as the access mode.

In Mac, Add the following line in your .bash_profile
```
source ~/.git-prompt.sh

export PS1='\[\e]0;\u@\h: \w\a\]${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;33m\]\w$(__git_ps1 " (%s)")\$\[\033[00m\] '
```
