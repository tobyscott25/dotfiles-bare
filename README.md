# Dotfiles

```sh
# Clone this repo as a bare repo
git clone --bare https://github.com/tobyscott25/dotfiles-bare.git $HOME/.cfg

# Create alias so you can manage it from anywhere
alias dots='git --git-dir=$HOME/.cfg/ --work-tree=$HOME'

# Configure local clone to only show tracked files when running "dots status" if you want to avoid clutter
dots config --local status.showUntrackedFiles no
```
