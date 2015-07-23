Alan's Dotfiles 
===============

Use my [vimrc config file](https://github.com/alanhamlett/dotfiles/blob/master/vimrc) to get a head-start with [Vim](http://www.vim.org/download.php).

Quick Install Commands
---------------------------

    git clone git://github.com/alanhamlett/dotfiles.git
    ln -sf $PWD/dotfiles/vimrc $HOME/
    git clone git://github.com/gmarik/vundle.git $HOME/.vim/bundle/vundle
    vim +BundleInstall +qall

Key Features
------------

* Code folding for bracket or indention based languages
* Edit multiple files in tabs using minibufexpl plugin
* Using the [Solarized](https://github.com/altercation/solarized#features) color scheme
* Using [Vundle](https://github.com/gmarik/vundle#about) for plugin management (apt-get for Vim plugins)
* Common swp, backup, & view directories (No more ~ files left around)
* Useful defaults (spaces instead of tabs, remove trailing newlines, etc.)

Plugins Included
----------------

* [Solarized Color Scheme](https://github.com/altercation/vim-colors-solarized) - colorscheme for the vim text editor
* [Airline](https://github.com/bling/vim-airline) - Lean & mean status/tabline for vim
* [Mini Buffer Explorer](https://github.com/fholgado/minibufexpl.vim#features-overview) - Elegant tab bar showing open files
* [Fugitive](https://github.com/tpope/vim-fugitive#fugitivevim) - the best Git wrapper of all time
* [Gundo](https://github.com/sjl/gundo.vim) - plugin to visualize your Vim undo tree
* [LargeFile](http://vim.sourceforge.net/scripts/script.php?script_id=1506) - edit large files quickly
* [CamelCaseMotion](https://github.com/bkad/CamelCaseMotion) - CamelCase motion through words
* [NERDTree](https://github.com/scrooloose/nerdtree) - file tree explorer plugin
* [WakaTime](https://github.com/wakatime/vim-wakatime) - automatic time tracking and metrics about your programming
* [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - code completion
* [Expand-Region](https://github.com/terryma/vim-expand-region) - visually select increasingly larger regions of text
* [CtrlP](https://github.com/kien/ctrlp.vim) - fuzzy file finder
* [Surround](https://github.com/tpope/vim-surround) - quoting/parenthesizing made simple
* [Syntastic](https://github.com/scrooloose/syntastic) - syntax checking
* [Python-Mode](https://github.com/klen/python-mode) - detect runtime errors in Python code

Screenshot
----------

![VimScreenShot](https://github.com/alanhamlett/dotfiles/raw/master/images/VimScreenShot.png)

Installation
------------

### Download and install my [vimrc](https://github.com/alanhamlett/dotfiles/raw/master/vimrc) file:

    git clone git://github.com/alanhamlett/dotfiles.git
    ln -sf $PWD/dotfiles/vimrc $HOME/

### Download and install [Vundle](https://github.com/gmarik/vundle#about), the vim plugin manager:

    git clone git://github.com/gmarik/vundle.git $HOME/.vim/bundle/vundle

### Install the Vim plugins using Vundle:

    vim +BundleInstall +qall

### Use a font patched for airline compatibility, like [Anonymous Pro](https://github.com/powerline/fonts/raw/master/AnonymousPro/Anonymice%20Powerline.ttf):

[Full list of fonts](https://github.com/powerline/fonts)

### Install the solarized color palette in your terminal:

[iTerm2](https://github.com/altercation/solarized/tree/master/iterm2-colors-solarized):

* Download [Solarized Dark.itermcolors](https://github.com/altercation/solarized/raw/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors).
* Open iTerm 2, open Preferences, click on the "Profiles" icon in the preferences toolbar, then select the "colors" tab.
* Click on the "load presets" and select "import...".
* Select the Solarized Dark theme file.

[Guake](https://github.com/coolwanglu/guake-colors-solarized):

    git clone git://github.com/coolwanglu/guake-colors-solarized.git
    ./guake-colors-solarized/set_dark.sh solarized

### Choose Solarized's light or dark theme in your vimrc file:

    set background=dark

More info on the official [Solarized page](https://github.com/altercation/solarized#features).
