Cloning this vim configuration
==============================
Installation:

    git clone git@github.com:tomsercu/dotvim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update

My notes
========
###Git and pathogen synchronization
Based on http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/ 
Intro to pathogen: http://addisu.taddese.com/blog/using-github-and-pathogen-for-your-vim-config-files/

### Inspiration for my configuration
http://stevelosh.com/blog/2010/09/coming-home-to-vim/#bundles-i-use
maybe later: https://github.com/carlhuda/janus
And of course spf13
Also http://stackoverflow.com/questions/357785/what-is-the-recommended-way-to-use-vim-folding-for-python-code

Plugins
=======
+ fugitive (git support)
+ easymotion


