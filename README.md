# vimfiles

~/.vim and ~/.vimrc configuration usgin [iTerm2](http://iterm2.com/) with 256 colors

![iTerm2 example](https://dl.dropboxusercontent.com/s/6wtbk0ae5v368tb/Screen%20Shot%202015-04-21%20at%2010.25.49%20PM.png)

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

