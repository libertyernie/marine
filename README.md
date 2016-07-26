marine
======

This proof-of-concept project builds SeaMonkey 2.35 against the platform used by the "Tycho" Pale Moon rebase (instead of Gecko 38.)

To build on Windows:
* Check this repository out recursively (to include Tycho)
* Add a file named .mozconfig with the contents: ac_add_options --enable-application=suite
* Install the mozilla-build package from Mozilla and Visual Studio 2013 Community Edition
* Run \mozilla-build\start-shell-msvc2013.bat to open a command prompt and go to the marine folder
* Run ./client.py checkout to get the SeaMonkey 2.35 versions of ChatZilla and DOM Inspector
* Run ./mozilla/mach build

The SeaMonkey code here is based on SEAMONKEY_2_35_RELEASE_BRANCH on comm-release (it may be missing some Thunderbird changes).
