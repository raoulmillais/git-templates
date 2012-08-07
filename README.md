My Git Templates
================

These will only work on unix as the hook scripts are bash.

Requirements
------------

* git 1.7.1 or newer
* bash

Setting up a default template
-----------------------------

cd into the template you want and set your templatedir to ensure all new repos
get these hooks:

    git config --global init.templatedir "`pwd`"


Choosing a specific template
----------------------------

    git init --template=<path>
