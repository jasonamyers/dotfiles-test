=== JAM dotfiles ===

This is my collection of dot files for my linux systems.

To use them:

* git clone it into your home directory
* rename your current .bash_profile .bashrc .vim .vimrc .zsh .zshrc
* ln -s ~/dotfiles/bash_profile .bash_profile
* ln -s ~/dotfiles/bashrc .bashrc
* ln -s ~/dotfiles/vimfolder .vim
* ln -s ~/dotfiles/vimrc .vimrc
* mkdir .config
* ln -s ~/dotfiles/terminator .config/terminator
* ln -s ~/dotfiles/fonts .fonts
* fc-cache -f -v
* ln -s dotfiles/xmonad .xmonad
* ln -s dotfiles/virtualenv .virtualenv
* ln -s dotfiles/oh-my-zsh .oh-my-zsh


You might also need the following first:

* git config --global color.ui auto
* git config --global core.autocrlf input
* git config --global user.name "Name"
* git config --global user.email "name@domain.com"
* git config --global core.excludesfile "~/.gitignore"
* add .DS_Store and thumbs.db to that file
* git config --global alias.lg "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%ci) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative --all"
* git config --global push.default=simple
* git config --global alias.pu=!git fetch origin -v; git fetch upstream -v; git merge upstream/master
