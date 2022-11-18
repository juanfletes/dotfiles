# dotfiles

My personal preference files "dotfiles" for Linux.

## Installation

### vimrc

The [vimrc] file is my configuration file for the *Vim* text editor, adding functionality and theme based in this article: [Vimrc Configuration Guide - How to Customize Your Vim Code Editor with Mappings, Vimscript, Status Line, and More](https://www.freecodecamp.org/news/vimrc-configuration-guide-customize-your-vim-editor).

The [vimrc] configuration can be installed with the
following command:

```bash
curl -fLo ~/.vimrc --create-dirs https://raw.githubusercontent.com/juanfletes/dotfiles/main/editors/vim/vimrc
```

### Full Installation

Full installation of my all dotfiles is using the [dotbot] installer, so
installation is relatively painless and non-destructive, this require only one command:

```bash
git clone https://github.com/juanfletes/dotfiles ~/.dotfiles && ~/.dotfiles/install
```

## Libraries/Standards Used

- [dotbot]: Dotfile installer
- [junegunn/vim-plug](https://github.com/junegunn/vim-plug): Vim plugin manager
- Various other Vim plugins, listed in detail in the [vimrc] file

[dotbot]: https://github.com/anishathalye/dotbot
[vimrc]: editors/vim/vimrc/vimrc
