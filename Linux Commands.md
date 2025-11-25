**File and Directory Management**
pwd → Show current working directory
ls → List files in the directory
			a. ls -l → Long listing (permissions, owner, size, date)
			b. ls -a → Show hidden files
cd <directory> → Change directory
			a. cd .. → Go back one directory
mkdir <dirname> → Create a new directory
rmdir <dirname> → Remove an empty directory
rm -r <dirname> → Remove directory with contents
touch <filename> → Create empty file
cp <source> <destination> → Copy files or folders
mv <source> <destination> → Move/rename files or folders
rm <filename> → Delete file

**File Viewing**
cat <file> → Show contents of a file
less <file> → View file page by page
head <file> → Show first 10 lines
tail <file> → Show last 10 lines
tail -f <file> → Continuously monitor file updates (useful for logs)

**System Info**
uname -a → Show system info (kernel, architecture, etc.)
hostname → Show system hostname
whoami → Show current logged-in user
uptime → Show system running time and load
date → Show current date & time
cal → Show calendar

**User Management**
who → Show who is logged in
id → Show current user ID & groups
su <user> → Switch user
sudo <command> → Run command as root

**Permissions**
ls -l → View permissions
chmod <permissions> <file> → Change file permissions
chown <user>:<group> <file> → Change file ownership

**Disk & Process Management**
df -h → Show disk usage
du -sh <dir> → Show size of a directory
free -h → Show memory usage
ps → Show running processes
ps aux | grep <name> → Search for a process
top → Real-time process monitoring
kill <pid> → Kill a process by ID

**Networking**
ping <host> → Check connectivity
ifconfig or ip a → Show IP addresses
netstat -tulnp → Show active connections/ports
scp <file> user@host:/path → Copy file to remote system
ssh user@host → Connect to remote system

**Archive & Compression**
tar -cvf archive.tar file1 file2 → Create tar archive
tar -xvf archive.tar → Extract tar archive
gzip file → Compress file
gunzip file.gz → Decompress file

**Search**
find /path -name <filename> → Find file by name
grep "text" <file> → Search text in file
grep -r "text" <dir> → Search text in directory recursively


