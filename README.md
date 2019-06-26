.vim
====

This is the modified version of [jessfraz/.vim](https://github.com/jessfraz/.vim/) config files, customised to suit my personal needs.

**Table of Contents**

<!-- toc -->

- [.vim](#vim)
  - [About](#About)
    - [Installing](#Installing)
    - [Pathogen](#Pathogen)

<!-- tocstop -->

## About

### Installing

```console
$ cd ~/
$ git clone --recursive https://github.com/abhisek/.vim.git .vim
$ ln -sf $HOME/.vim/vimrc $HOME/.vimrc
$ cd $HOME/.vim
$ git submodule update --init
```

### Pathogen
The vim dot files make use of the excellent [Pathogen](https://github.com/tpope/vim-pathogen) runtime path manager to install plugins and runtime files into their own private directiories.

Currently using version 2.4 of Pathogen
