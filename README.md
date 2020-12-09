# To set up a new computer:

Create a new ssh key with ssh-keygen (default settings). Give the public key to github at https://github.com/settings/keys .

Install [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)

## For Mac

Upgrade to latest OS and install developer tools (run `git --help` at a terminal and it will prompt to install tools).

Install homebrew: https://brew.sh/

## Generic

Install gvm, then install binary go (as otherwise there is a bootstrapping issue): `gvm install go1.15 -B && gvm use go1.15 --default`.

git@github.com:lesam/telegraf.git

Install stow, tmux

```bash
# Mac:
brew install stow tmux
# Debian/Ubuntu
apt-get install stow tmux
```
Get the dotfiles with stow:

```
cd ~/
git clone git@github.com:lesam/stow-dotfiles.git
cd stow-dotfiles
stow dotfiles
```
