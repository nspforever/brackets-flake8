#Brackets-FLAKE8

This extension add pep8 style guide check for python projects.

##Install from URL

1. Open the the Extension Manager from the File menu
2. Copy paste the URL of the github repo or zip file


##Install from file system

1. Download this extension using the ZIP button above and unzip it.
2. Copy it in Brackets' `/extensions/user` folder by selecting `Help > Show Extension Folder` in the menu.
3. Reload Brackets.

##Instructions

== Dependencies ==

* flake8
  - sudo apt-get install python-flake8
  - sudo pip install flake8 --upgrade

After installed, simple use Ctrl+Shift+P or View->FLAKE8 Lint on your python code.
If doesn't works, find the path of flake8 on your system and edit the file
~/.config/Brackets/extensions/user/brackets-pep8/defaultPreferences.js and set
flake8Path accordingly.