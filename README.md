# Vim configuration to use with tmux

## Install steps:

### 1. create .vimrc that will include vimrcg and setup plugin dir for perl-support

source $HOME/.vim/vim/.vimrc_g

let g:Perl_PluginDir = $HOME.'/.vim/bundle/vim-plugins/'

### 2. install Vundle to .vim

mkdir ~/.vim/bundle

git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

### 3. Clone this vim repo:

git clone https://github.com/dzehv/vim.git ~/.vim/vim

### 3. install ctags

http://prdownloads.sourceforge.net/ctags/ctags-5.8.tar.gz

### 4. install plugins:

Launch vim and type :PluginInstall

or vim +PluginInstall +qall

### 5. install xterm and env variable

echo export TERM=xterm-color >> ~/.bashrc

### 6. make tmux using xterm-color (or clone tmux conf from [dzehv/tmux](https://github.com/dzehv/tmux))
