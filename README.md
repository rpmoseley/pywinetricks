This project provides a python implementation of the original 'winetricks' project, and tries to adhere to the same level of license.

Rather than being a large single shell script it splits the various commands into separate modules and invokes them as required, it supports both the 
wine32 and wine64 executables using the same logic as the distributed script found in /usr/bin/wine-stable on Debian systems.

The main entry script will remain named 'winetricks', and accept the same arguments in order to as backward compatible as possible.
