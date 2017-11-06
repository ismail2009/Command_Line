# Command_Line

Styling Terminal
********************
- Click it and the Preferences window will appear

![alt text](https://www.maketecheasier.com/assets/uploads/2017/01/command-line-terminal-edit-preferences-menu-general-tab.png)


- Moving on, the Colors tab, as the name suggests, contains all the color-related settings for the terminal window

![alt text](https://www.maketecheasier.com/assets/uploads/2017/01/command-line-terminal-edit-preferences-menu-colors-tab.png)

- By default, the “Use colors from system theme” option is active. Just disable it, and you can choose from built-in schemes. For example, I selected the ‘Black on light yellow’ scheme for my terminal.


Using Shortcuts in Terminal
********************************

Alias mainly used for abbreviating a system command, or for adding default arguments to a regularly used command.

- ls -la
- atom .bashrc

Add your new aliases

- alias search='apt-cache search'
- alias install='sudo apt-get install'

******************************************

Package Management
Several tools are available for interacting with Ubuntu's package management system, from simple command-line utilities
- dpkg:
dpkg is a package manager for Debian-based systems. It can install, remove, and build packages, but unlike other package management systems, it cannot automatically download and install packages or their dependencies. This section covers using dpkg to manage locally installed packages:
- You can install a local .deb file by entering:
sudo dpkg -i zip_3.0-4_i386.deb
