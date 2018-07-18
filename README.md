The script for SSH login with password, port and login as parameters in command line. It's written in expect language. After login, it passes control to user. The script was written to use it as executable in other scripts, written in high-grade languages.<br>
Also the script adds hotkeys into remote console. More information in script's comments.

Usage:<br>
logino.exp ip password loginname port<br>
All parameters are necessary.

Also, package "expect" have to be installed, it can be done with:<br>
Debian like os: sudo apt-get install expect<br>
Centos: sudo yum install expect<br>
FreeBSD: sudo rm -rf / and install normal os.
