## Debian
These are scripts to run in order to get the minimal Debian system configured the way I like. 

These scripts are simple commands to install packages and setup a few things.

### First
This script should be executed by root user.
This script changes sources.list to enable all repository of Jessie and update them.
Then install sudo and add user(elliot) to sudo group.

### Second
This script should be executed by elliot(non-root user).
This script first install network manager, wireless tools and driver for my wifi card.
Then it enable network-manager to manager ethernet.
Then it installs packages including i3, vim, tmux, et cetera.
Also starts ssh server and enable it to start with boot.
It then configure i3 using my dotfiles. And do some little configurations


