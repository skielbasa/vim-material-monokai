# Material Monokai Color Scheme for Vim

Inspired by brendanblackwood's [material-monokai-syntax theme](https://github.com/brendanblackwood/material-monokai-syntax), my favorite Atom Syntax theme.

This theme uses sickill's [vim-monokai](https://github.com/sickill/vim-monokai) as a base with its colors shifted to the Material Design color palette. It is recommended that you use a [matching terminal theme](https://github.com/MartinSeeler/iterm2-material-design).

> **NOTE:** A terminal that supports true colors is strongly recommended. There is a 256 color fallback, but it doesn't look that great.

## Screenshots

![Material Monokai](https://i.imgur.com/oDzQb5A.png)

## Installation

Install this color scheme using your preferred Vim plugin manager, then add the following to your .vimrc file:

```vim
set background=dark
set termguicolors
colorscheme material-monokai
```

### Options

Enable italic comments (terminal permitting) by adding the following to your .vimrc file:
```vim
let g:materialmonokai_italic=1
```

### Vim Airline Support
Includes a matching [Airline](https://github.com/vim-airline/vim-airline) theme. To activate it, add the following to your .vimrc file:
```vim
let g:airline_theme='materialmonokai'
```
