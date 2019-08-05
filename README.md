# My personal dotfiles

Based on https://medium.com/toutsbrasil/how-to-manage-your-dotfiles-with-git-f7aeed8adf8b

## Setup environment in a new computer

- Clone repository `git clone --bare git@github.com:juanpmarin/dotfiles.git $HOME/.dotfiles`
- Define alias `alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'`
- checkout the actual content from the git repository `dotfiles checkout`
