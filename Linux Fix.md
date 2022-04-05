## Linux Fixes

to fix bluetooth

sudo apt-get install pulseaudio-module-bluetooth
sudo killall pulseaudio
pulseaudio --start    
sudo systemctl restart bluetooth

to fix kernel issues

dpkg-reconfigure -a


