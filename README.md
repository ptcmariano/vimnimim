# Vimnimim

Just another vimrc configuration.

**Fundamentals:**
* Vim defaults as much as possible;
* Fewer plugins;
* No autocomplete;
* *Need oriented settings*

## Install

The process below will write/change the `.vimrc` file content.

```
$ git clone https://github.com/ptcmariano/vimnimim.git ~/.vimnimim
$ cd ~/.vimnimim
$ sh install.sh
```
Start your vim.

## Update
To update your vim-master with latest features, just run the following command:

```
$ cd ~/.vimnimim && sh update.sh
```

## Uninstall
To disable configs from vimnimim, just rewrite your `.vimrc` file with your own
configs, or keep it empty.

To complete remove vimnimim files:
```
$ rm -r ~/.vimnimim
```

### Requeriments
* Make sure you have `vim-gtk` or `vim-gnome` package installed so copy and
  paste can work well with system's clipboard
* flake8 is needed to Python checks.
* xclip is needed to copy and paste work on NeoVim


*This project started as a fork from
[vim-master](https://github.com/cacarrara/vimnimum) and will not exist
without its previous work.*
