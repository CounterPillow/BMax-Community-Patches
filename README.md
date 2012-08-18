Community Patched BlitzMax BRL Modules
======================================

Introduction
------------

These modules are modules from the BRL and pub modscope for Blitzmax, patched with community submitted fixes for various bugs or issues.

The original source code originates from Blitz Research LTD (and various library authors) and is licensed under the terms and conditions of the zlib license in the brl.mod modscope, and public domain/whatever is stated in the file headers or LICENSE files inside the pub modscope.

The community patches come from a multitude of BlitzMax users and try to maintain the modules in a way that they can be used in production. The patches are also licensed under the terms and conditions of the zlib license, or whatever license the file is they apply to.

Installation
------------

Delete the original brl.mod and pub.mod, clone the git repo and replace your brl.mod and pub.mod folders by those in the git repository.
You can also git-init the mod directory and add the remote manually, as git clone only allows you to clone into empty directories.
Example:

    cd mod/
    git init .
    git remote add upstream git://github.com/CounterPillow/BMax-Community-Patches.git
    git pull upstream master

After that, rebuild the modules (and documentation) either with bmk or inside the BlitzMax IDE.
