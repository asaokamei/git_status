git_status
==========

show git status for all the sub directories. 

installaton
-----------

download git_status from github, and:

    mv git_status /usr/local/bin
    chmod +x /usr/local/bin/git_status

requirement: php at /usr/bin/php. 

###example of outpout:

    ---------------
    PATH: /works/works/WScore-dev
    ---------------
    /
    # On branch master
    # Changes to be committed:
    #   (use "git reset HEAD <file>..." to unstage)
    #
    #  new file:   git_status
    #
    # Changes not staged for commit:
    #   (use "git add <file>..." to update what will be committed)
    #   (use "git checkout -- <file>..." to discard changes in working directory)
    #
    #	modified:   composer.lock
    #
    ---------------
    /vendor/wscore/validation/
    # On branch master
    nothing to commit (working directory clean)
    ---------------

