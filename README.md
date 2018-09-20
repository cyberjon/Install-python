# Install-python
sudo add-apt-repository --remove ppa:fkrull/deadsnakes;
sudo apt-get remove --purge python3.6;
sudo apt-get remove --purge python3.5;
sudo apt autoremove python;
git clone https://github.com/cyberjon/Install-python.git;
cd Install-python;
sh install.sh
