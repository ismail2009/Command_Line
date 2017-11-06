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
2- Apt:
The apt command is a powerful command-line tool, which works with Ubuntu's Advanced Packaging Tool (APT) performing such functions as installation of new software packages, upgrade of existing software packages, updating of the package list index, and even upgrading the entire Ubuntu system.
- Install a Package: Installation of packages using the apt tool is quite simple. For example, to install the network scanner nmap, type the following:
sudo apt install nmap
- Update the Package Index: The APT package index is essentially a database of available packages from the repositories defined in the /etc/apt/sources.list file and in the /etc/apt/sources.list.d directory. To update the local package index with the latest changes made in the repositories, type the following:
sudo apt update
- Upgrade Packages: Over time, updated versions of packages currently installed on your computer may become available from the package repositories (for example security updates). To upgrade your system, first update your package index as outlined above, and then type:
sudo apt upgrade
- Aptitude
Aptitude is best suited for use in a non-graphical terminal environment to ensure proper functioning of the command keys. You may start the menu-driven interface of Aptitude as a normal user by typing the following command at a terminal prompt:
You can also use Aptitude as a command-line tool, similar to apt. To install the nmap package with all necessary dependencies, as in the apt example, you would use the following command:
sudo aptitude install nmap
