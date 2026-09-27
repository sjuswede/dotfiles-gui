# dotfiles
The towed dotfiles for various gui software running under my normal Linux install.

## Requirements

Ensure you have the following installed on your system

### Git

```
dnf install git
```

### Stow

```
dnf install stow
```

Install into $HOME using

```
$ git clone git@github.com:sjuswede/dotfiles-gui.git
```

Renaming the dotfile directory to .dotfile might be handy.

```
mv ~/dotfiles-gui ~/.dotfiles-gui
```

The structure is one directory per program. This allows for stow'ing only select programs as required.

For example:

```
stow alacritty
```


