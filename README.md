sky-dotfiles
============

    cd ~
    rvm gemset use global
    gem install homesick
    homesick clone bskyb-commerce-helpcentre/sky-dotfiles
    cd ~/.homesick/repos/bskyb-commerce-helpcentre/sky-dotfiles/home
    git submodule update --init
    cd ~/.homesick/repos/bskyb-commerce-helpcentre/sky-dotfiles/home/.vim
    git submodule update --init
    homesick symlink bskyb-commerce-helpcentre/sky-dotfiles
