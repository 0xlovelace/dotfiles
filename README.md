# Nomadic Pickle's Config Files

## Prerequisites 
### Tools 

- zsh
- ohmyzsh
- powerlevel10k
- Patched Nerd Font (Fira Code Nerd Font)

## Install

> Use the command below in a bash terminal.

```bash
git clone --bare git@github.com:nomadicpickle/dotfiles.git $HOME/.cfg
cd ~/.cfg
git --git-dir=$HOME/.cfg --work-tree=$HOME config --local status.showUntrackedFiles no
git --git-dir=$HOME/.cfg --work-tree=$HOME checkout
source ~/.zshrc
```
