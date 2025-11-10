# linux-usefull-for-me-commands
useful and daily linux commands and configurations

My Linux Learning Journey

A personal collection of **commands**, **configurations**, and **tips** I use daily since I started learning Linux.  
This repository helps me keep track of what I’ve learned and serves as a quick reference for the future.

# System info
uname -a
lsb_release -a
hostnamectl

# File & directory operations
ls -ali or ls -lih
cd /path/to/dir
cp source.txt destination.txt
mv oldname.txt newname.txt
rm -rf /path/to/file_or_folder
mkdir new_folder
touch newfile.txt

# Viewing and editing
cat filename.txt
less filename.txt
nano filename.txt
vim filename.txt

# Permissions
chmod +x script.sh
chmod 644 scriph.sh
chown user:group file.txt

# Update system
sudo apt update && sudo apt upgrade

# Manage services
sudo systemctl status ssh
sudo systemctl start ssh
sudo systemctl enable ss

# View running processes
top
htop
ps aux | grep process_name

# Check network info
ip a
ping google.com
netstat -tulnp
ss -tulpen
curl ifconfig.me

# Connect to remote server
ssh user@host



