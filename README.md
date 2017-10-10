Sublime Text 3 Settings
=======================

Backup of my own Sublime Text 3 settings. Inspired from the zessx [repos](https://github.com/zessx/st3-settings/) and [tuto](https://blog.smarchal.com/configurer-sublime-text-en-30-secondes-grace-a-git).
This repo allows you to quickly install a fully configured Sublime Text 3 with:

 - the awesome [Package Control](https://github.com/wbond/sublime_package_control)
 - useful packages for python development
 - a custom keymap
 - custom preferences

Windows
-------

    cd %APPDATA%/Sublime Text 3
    git init
    git remote add origin https://github.com/emmanuelolivier/st3-settings.git
    git fetch
    git checkout -t origin/master

Linux
-----

    cd ~/.config/sublime-text-3
    git init
    git remote add origin https://github.com/emmanuelolivier/st3-settings.git
    git fetch
    git checkout -t origin/master

OS X
----

    cd ~/Library/Application Support/Sublime Text 3
    git init
    git remote add origin https://github.com/emmanuelolivier/st3-settings.git
    git fetch
    git checkout -t origin/master
