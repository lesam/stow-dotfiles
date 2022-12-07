# To set up a new computer:

Create a new ssh key with ssh-keygen (default settings). Give the public key to github at https://github.com/settings/keys .

Install [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)

## For Mac

Upgrade to latest OS and install developer tools (run `git --help` at a terminal and it will prompt to install tools).

Install homebrew: https://brew.sh/ (brew will not be on the PATH yet, this is ok)

Install pyenv to replace system python with python3 (install with brew)

## Generic

Install gvm, then install binary go (as otherwise there is a bootstrapping issue): `gvm install go1.15 -B && gvm use go1.15 --default`.

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
