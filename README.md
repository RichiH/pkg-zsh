This is my personal packaging repository for Zsh in Debian.

Personal cheat-sheet below:

    [core]
    	repositoryformatversion = 0
    	filemode = true
    	bare = false
    	logallrefupdates = true
    [remote "origin"]
    	url = git@github.com:RichiH/pkg-zsh.git
    	fetch = +refs/heads/*:refs/remotes/origin/*
    [branch "master"]
    	remote = origin
    	merge = refs/heads/master
    [remote "upstream"]
    	url = git://zsh.git.sf.net/gitroot/zsh/zsh
    	fetch = +refs/heads/*:refs/remotes/upstream/*
    [branch "upstream"]
    	remote = upstream
    	merge = refs/heads/master
    [remote "ft"]
    	url = git://github.com/ft/pkg-zsh.git
    	fetch = +refs/heads/*:refs/remotes/ft/*
    [branch "ft/debian"]
    	remote = origin
    	merge = refs/heads/ft/debian
    [remote "xtaran"]
    	url = git://github.com/xtaran/pkg-zsh.git
    	fetch = +refs/heads/*:refs/remotes/xtaran/*
    [branch "xtaran/debian"]
    	remote = origin
    	merge = refs/heads/xtaran/debian
