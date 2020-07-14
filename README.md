# elementary-os-changes
Changes at elementary OS after installation

#!/bin/sh

sudo apt-get check
sudo apt-get update
sudo apt-get update --allow-releaseinfo-change
sudo apt-get upgrade -y
sudo apt-get upgrade --with-new-pkgs
sudo apt-get dist-upgrade -y
sudo apt autoremove -y
sudo apt-get autoclean
sudo apt clean

exit
