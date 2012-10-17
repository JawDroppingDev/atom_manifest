atom_manifest
=============

The manifest for the Intel Atom board used in our project.

Get Repo
--------

    mkdir ~/bin
    export PATH=~/bin:$PATH
    curl https://dl-ssl.google.com/dl/googlesource/git-repo/repo > ~/bin/repo
    chmod a+x ~/bin/repo

Syncing the Source
---------------------------------------

    mkdir ~/JDD
    cd ~/JDD
    repo init -u https://github.com/JawDroppingDev/atom_manifest -b master
    repo sync -j16
