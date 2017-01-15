## settings

settings i used for development environments



### VIM setting files

- .vimrc
- colors(molokai) from [`https://github.com/tomasr/molokai`](https://github.com/tomasr/molokai)




#### color themes

http://cocopon.me/app/vim-color-gallery/



#### Plugins

- 'gmarik/Vundle.vim' "required - *For plugin install* 'tpope/vim-fugitive' "required - *For Git*


- 'tmhedberg/SimpylFold' - *Folding* [link](https://github.com/tmhedberg/SimpylFold)

- 'nvie/vim-flake8' - *Syntax check* [link](https://github.com/nvie/vim-flake8)

- 'scrooloose/nerdtree' - *directory tree* [link](https://github.com/scrooloose/nerdtree)

- 'jistr/vim-nerdtree-tabs' - *directory tree* [link](jistr/vim-nerdtree-tabs)

- 'scrooloose/nerdcommenter' - *directory tree* [link](https://github.com/scrooloose/nerdcommenter)

- 'Lokaltog/powerline', {'rtp': 'powerline/bindings/vim/'} - *below status bar* [link](https://github.com/Lokaltog/vim-powerline)

- 'mattn/emmet-vim' - *expanding abbreviations* [link](https://github.com/mattn/emmet-vim)

  ​


#### Commands

**Install command** : `:PluginInstall`

**syntax check** :  `F7`

**show tree** : `Ctrl+n`

**Folding** : `space`



![vim_screenshot](vim_screenshot.png)

*To solve `value Error:unkown locale: UTF-8`*

`export LC_ALL=en_US.UTF-8` and `export LANG=en_US.UTF-8`