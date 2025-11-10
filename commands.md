# My Linux Commands & Daily Configurations

A collection of commands and configurations I use daily since I started learning Linux.

# System info

```bash
uname -a
lsb_release -a
hostnamectl
```

# File & directory operations
```bash
ls -ali or ls -lih
cd /path/to/dir
cp source.txt destination.txt
mv oldname.txt newname.txt
rm -rf /path/to/file_or_folder
mkdir new_folder
touch newfile.txt
```

# Viewing and editing

```bash
cat filename.txt
less filename.txt
nano filename.txt
vim filename.txt
```

# Permissions
```bash
chmod +x script.sh
chmod 644 script.sh
chown user:group file.txt
```

# Update system
```bash
sudo apt update && sudo apt upgrade
```

# Manage services
```
sudo systemctl status ssh
sudo systemctl start ssh
sudo systemctl enable ssh
```

# View running processes
```bash
top
htop
ps aux | grep process_name
```

# Check network info
```bash
ip a
ping google.com
netstat -tulnp
ss -tulpen
curl ifconfig.me
```

# Connect to remote server
```bash
ssh user@host
```

# GUI move windows
```
Hotkey + left mouse key
```

# GUI resize window
```bash
Hotkey + right mouse key
```

# Generate public and private key
```bash
ssh-keygen -t ed25519 -C "your_email@example.com" -f ~/.ssh/id_ed25519
-t = type
-C = comment
-f = file path
# show public key
cat ~/.ssh/id_ed25519.pub
# check/verify key
ssh-keygen -lf ~/.ssh/id_ed25519.pub
# change file permission for public and private key
chmod 600 ~/.ssh/id_ed25519
chmod 644 ~/.ssh/id_ed25519.pub
```





This list grows as I learn more about Linux — it’s my daily quick reference
