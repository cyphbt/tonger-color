# tonger-color



// Work-In-Progress

An color scheme plugin for [PaperColor-Theme](https://github.com/NLKNguyen/papercolor-theme)

All features are as in PaperColor-Theme

## Installation

*Manually:* Install [PaperColor-Theme](https://github.com/NLKNguyen/papercolor-theme)

Then place `PaperColor_tonger.vim` file from this repository into `autoload` folder within your Vim directory, e.g. `~/.vim/autoload/`

*Using a plugin manager like [vim-plug](https://github.com/junegunn/vim-plug)* (recommended for easy `:PlugInstall`):

```VimL
Plug 'NLKNguyen/papercolor-theme' " required
Plug 'cypj/tonger-color'
```

Then, put this in your `~/.vimrc`

```VimL
let g:PaperColor_Theme = 'tonger'
colorscheme PaperColor
```