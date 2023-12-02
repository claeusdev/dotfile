# dotfile

1. Clone repo
2. `ln -s ~/.dotfiles/.gitconfig ~/.gitconfig` && `ln -s ~/.dotfiles/.zshrc ~/.zshrc` # will make this an install script later.
3. ```sh
   # install homebrew
   # pass Brewfile location
   brew bundle --file ~/.dotfiles/Brewfile
   cd .dotfiles
   brew bundle
