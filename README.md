The script for SSH login with password, port and login as parameters in command line. It's written in expect language. After login, it passes control to user. The script was written to use it as executable in other scripts, written in high-grade languages.
Also the script adds hotkeys into remote console. More information in script's comments.

Usage:
logino.exp ip password loginname port
All parameters are necessary.

Also, package "expect" have to be installed, it can be done with:<br>
Debian like os: sudo apt-get install expect
Centos: sudo yum install expect
FreeBSD: sudo rm -rf / and install normal os.
