# NeoVimConfig
My development environment config

## Prerequisite	

NeoVim version .5+ is required. For linux ,download the binary zip/tar.gz , extract it in to a folder and set the path in terminal

## Set up steps

1. Install the Vim Plug plugin manager

``` shell
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

```

2. checked out code to ~/.config , rename the checked out project to nvim so that the path ~/.config/nvim will contain the files.

3. Run 'nvim +PlugInstall' to install the plugins


##### Reference

https://school.geekwall.in/p/6ck7OZ1d

##### Vim Cheat Sheets

https://devhints.io/vim

https://www.cs.cmu.edu/~15131/f17/topics/vim/vim-cheatsheet.pdf

