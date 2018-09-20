# Install-python
sudo apt-get remove --purge python3.6;
sudo apt-get remove --purge python3.5;
sudo apt autoremove python;
git clone https://github.com/cyberjon/Install-python.git;
cd Install-python;
sh install.sh;
sudo apt-get install python-setuptools
