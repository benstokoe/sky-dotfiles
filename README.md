sky-dotfiles
============

    cd ~
    rvm gemset use global
    gem install homesick
    homesick clone bskyb-commerce/sky-dotfiles
    cd ~/.homesick/repos/bskyb-commerce/sky-dotfiles
    git submodule update --init
    cd ~/.homesick/repos/bskyb-commerce/sky-dotfiles/home/.vim
    git submodule update --init
    homesick symlink bskyb-commerce/sky-dotfiles
    
    Install Vundler for vim (if you're using it) 
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
