marine
======

This proof-of-concept project builds SeaMonkey 2.35 against the "Tycho" Pale Moon rebase.

To build on Windows:
* Check this repository out recursively (to include Tycho)
* Add a file named .mozconfig with the contents: ac_add_options --enable-application=suite
* Install the mozilla-build package from Mozilla and Visual Studio 2013 Community Edition
* Run \mozilla-build\start-shell-msvc2013.bat to open a command prompt and go to the marine folder
* Run ./client.py checkout to get the SeaMonkey 2.35 versions of ChatZilla and DOM Inspector
* Run ./mozilla/mach build
