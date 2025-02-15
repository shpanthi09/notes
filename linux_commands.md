# Linux commands 
# File and Directory Operations:
List directory contents
ls -l – Long format with file details
ls -a – List all files, including hidden ones
cd – Change directory
cd /path/to/directory
pwd – Print working directory
mkdir – Make a new directory
mkdir new_folder
rmdir – Remove empty directory
rmdir folder_name
rm – Remove files or directories
rm file_name
rm -r directory_name – Recursive delete for directories
touch – Create a new empty file
touch file_name.txt
cp – Copy files or directories
cp file1.txt file2.txt
cp -r folder1 folder2 – Copy directory recursively
mv – Move or rename files or directories
mv old_name.txt new_name.txt
mv file.txt /path/to/directory/
find – Search for files or directories
find /path -name "filename"

# File Viewing and Editing:
cat – Concatenate and display file content
cat file.txt
less – View content of a file one screen at a time
less file.txt
more – Similar to less, but with limited features
head – Display the first 10 lines of a file
head file.txt
tail – Display the last 10 lines of a file
tail file.txt
tail -f file.txt – Follow the file (useful for logs)
nano – Text editor (simple)
nano file.txt
vim or vi – Text editor (advanced)
vim file.txt

# System Information:
uname – Display system information
uname -r – Kernel version
top – Show active processes in real-time
ps – View current processes
ps aux – List all processes
df – Show disk space usage
df -h – Human-readable format
du – Show disk usage of files and directories
du -sh * – Show total size of each file/folder
free – Display memory usage
free -h – Human-readable format
uptime – Show how long the system has been running
hostname – Show system’s hostname
dmesg – Display system messages, usually boot-related
lscpu – Show CPU architecture information

# File Permissions:
chmod – Change file permissions
chmod 755 file.txt – Set rwxr-xr-x permissions
chown – Change file owner and group
chown user:group file.txt
chgrp – Change group ownership
chgrp group_name file.txt

# User Management:
whoami – Show current logged-in user
id – Show user and group IDs
useradd – Add a new user
usermod – Modify an existing user
userdel – Delete a user
groupadd – Create a new group
passwd – Change a user’s password
sudo – Execute commands as another user, typically root
sudo command

# Networking:
ping – Send ICMP echo request to test connectivity
ifconfig or ip a – Display network interfaces
netstat – Display network connections, routing tables, etc.
ssh – Secure Shell for remote login
ssh user@hostname
scp – Secure copy for copying files between hosts
scp file.txt user@hostname:/path/to/destination
curl – Transfer data from or to a server
curl http://example.com
wget – Download files from the web
wget http://example.com/file.txt

# Package Management (Debian-based example):
apt-get – Package management for installing/updating/removing software
sudo apt-get install package_name
sudo apt-get update – Update package list
sudo apt-get upgrade – Upgrade installed packages
sudo apt-get remove package_name – Remove package

# Archiving and Compression:
tar – Create and extract tarballs
tar -cvf archive.tar file_or_directory – Create archive
tar -xvf archive.tar – Extract archive
gzip – Compress files
gzip file.txt – Compress
gunzip file.txt.gz – Decompress
zip and unzip – Compress and extract ZIP archives
zip archive.zip file1 file2
unzip archive.zip

# Miscellaneous:
echo – Print text to the terminal
echo "Hello, world!"
date – Display or set the system date and time
history – Show command history
alias – Create shortcuts for commands
alias ll="ls -l"
clear – Clear the terminal screen
exit – Exit the terminal or shell session
shutdown – Shutdown the system
sudo shutdown -h now – Shutdown immediately
reboot – Reboot the system
sudo reboot 

# Searching:
grep – Search for patterns within files
grep "pattern" file.txt
grep -r "pattern" /path/to/directory/ – Search recursively
which – Locate a command
which command_name
locate – Find files by name (requires updated database)
locate filename
