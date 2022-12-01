# Linux Fixes

- [Linux Fixes](#linux-fixes)
  - [To Fix Audio Issues](#to-fix-audio-issues)
  - [Fix kernel issues with alternate kernel running](#fix-kernel-issues-with-alternate-kernel-running)
  - [Configure git](#configure-git)
  - [To modify deb sources list](#to-modify-deb-sources-list)
  - [Top 15 Linux Apps](#top-15-linux-apps)
  - [Linux Commands](#linux-commands)

## To Fix Audio Issues

- sudo apt-get install pulseaudio-module-bluetooth
- sudo killall pulseaudio
- pulseaudio --start  
sudo systemctl restart bluetooth

## Fix kernel issues with alternate kernel running

dpkg-reconfigure -a

## Configure git

- git config --global user.name "your_name"
- git config --global user.email "your_email_address"

## To modify deb sources list

sudo nano /etc/apt/sources.list

## Top 15 Linux Apps

1. Rambox - Chatbox
2. Stacer - System Cleaner
3. Calibre - Ebook Reader
4. TimeShift -  System Backup
5. Tweaks - System Tweaks
6. KdenLive - Video Editor
7. Nitroshare - File Sharing

## Linux Commands

1. ls
   1. ls -a
   2. ls -al
2. pwd
3. cd
   1. cd ...
4. touch
5. echo $text > $fileName.ext
6. cat
7. mkdir
8. cp
9. mv
10. rm
11. rm -r
12. rmdir
13. htop
