    git clone git@github.com:beyond613/vimrc.git  ~/.vim
	mkdir ~/.tmp
	ln -s ~/.vim/.vimrc ~/
	cd ~/.vim
    git submodule init
    git submodule update
	vim +BundleInstall
