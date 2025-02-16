## Install Parsec on Debian 12

I had some errors when trying to install this on my Debian 12 installation. Some jpeg library error due to a library does not exist in 12 so a symlink and fake package install was my clutch for this.

Usage: (on your local machine, host is localhost and connection local)

sudo ansible-playbook parsec-install.yml
