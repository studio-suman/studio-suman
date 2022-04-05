## Linux Fixes

to fix bluetooth

sudo apt-get install pulseaudio-module-bluetooth
sudo killall pulseaudio
pulseaudio --start    
sudo systemctl restart bluetooth

to fix kernel issues with alternate kernel running

dpkg-reconfigure -a

configure git

git config --global user.name "your_name"
git config --global user.email "your_email_address"
