Configuration files.

Typical commands to use the configuration on a new PC:

```bash
git clone https://github.com/mikhailremnev/dotfiles.git
mkdir -p ~/.config/{i3,i3status}
ln -sv $PWD/dotfiles/i3/config ~/.config/i3/config
ln -sv $PWD/dotfiles/i3status/config ~/.config/i3status/config
```


Vim
------------------------------------------------

I am using Vundle to install the plugins:

```bash
### Link vimrc file to your .vim directory
ln -sv $PWD/dotfiles/vim/vimrc ~/.vim/vimrc
### Install plugin manager to ~/.vim/
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
### Install plugins from vimrc
vim -c PluginInstall
### 
```

If you want to use YouCompleteMe, see here:

### YouCompleteMe

TODO: Upload an example ycm_extra_conf.py file for the C++ project.


