## settings

settings i used for development environments



### VIM setting files

- .vimrc
- colors(molokai) from [`https://github.com/tomasr/molokai`](https://github.com/tomasr/molokai)




#### Plugins

- 'gmarik/Vundle.vim' "required - *For plugin install*


- 'tpope/vim-fugitive' "required - *For Git*


- 'tmhedberg/SimpylFold' - *Folding*
- 'nvie/vim-flake8' - *Syntax check*
- 'scrooloose/nerdtree' - *directory tree*
- 'jistr/vim-nerdtree-tabs' - *directory tree*
-  'scrooloose/nerdcommenter' - *directory tree*
-  'Lokaltog/powerline', {'rtp': 'powerline/bindings/vim/'} - *below status bar*
- 'mattn/emmet-vim' - *expanding abbreviations*



#### Commands

**Install command** : `:PluginInstall`

**syntax check** :  `F7`

**show tree** : `Ctrl+n`

**Folding** : `space`



![vim_screenshot](vim_screenshot.png)

*To solve `value Error:unkown locale: UTF-8`*

`export LC_ALL=en_US.UTF-8` and `export LANG=en_US.UTF-8`