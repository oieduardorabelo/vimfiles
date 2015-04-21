# vimfiles

~/.vim and ~/.vimrc configuration

# Installation

```
git clone --recursive https://github.com/oieduardorabelo/vimfiles.git ~/.vimfiles
ln -s ~/.vimfiles/vim.symlink ~/.vim
ln -s ~/.vimfiles/vimrc.symlink ~/.vimrc
vim +PluginInstall +qall
```

For `command-t`, you need to do:

```
cd ~/.vim/bundle/command-t/ruby/command-t
ruby extconf.rb
make
```

# License
[http://eduardorabelo.mit-license.org/](http://eduardorabelo.mit-license.org/)

