# dotfiles
```
# Get Homebrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install git
brew install wget

# git configurations
git config --global user.name "Seu Nome"
git config --global user.email seu_usuario@seuemail.com
git config --global core.editor vim
wget https://raw.githubusercontent.com/git/git/master/contrib/completion/git-completion.bash
wget https://raw.githubusercontent.com/git/git/master/contrib/completion/git-prompt.sh
# hiding config git files
mv ~/git-completion.bash ~/.git-completion.bash
mv ~/git-prompt.sh ~/.git-prompt.sh

# Get updated VIM
brew install vim
### reload bash after this :)

# Install vim-plug
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

```
