======================
Small Utils Collection
======================
Requirements
============
Tobe added...

Installation
============

Clone the Git Repo from github:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    git clone git://github.com/zer4tul/utils.git ~/utils

Add it to your $PATH variable:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    sed -e "s#PATH=.*#PATH=$PATH:$HOME/utils#" > ${HOME}/.bashrc.new

Compare ${HOME}/.bashrc and ${HOME}/.bashrc.new, the only difference should be $PATH has added $HOME/utils.

Use the new bashrc file:
^^^^^^^^^^^^^^^^^^^^^^^^^^^
    mv ${HOME}/.bashrc.new ${HOME}/.bashrc
    source .bashrc
