Update new subsystem:
sudo apt-get update --fix-missing: updates the list of packages and their versions, but does not install or upgrade anything
sudo apt-get upgrade: installs updates

Install C and C++:
sudo apt install gcc
sudo apt install g++

Vim:
vim <filename> to open file
Inside of vim, use 'a' or 'i' to edit a file, and escape to stop editing
':x' saves and closes
':w' saves
':q' closes
Use '!' to overide a command


To generate an rsa key:
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

Configure local git settings:
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
git config --global core.editor vim
