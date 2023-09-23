# Github Doc Example

## Step 1 - using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to copy and paster their code to replicate or research issues.c


In order to creatr codeblocks, you need to use three backticks (```)

RedHat Linux Command:

```
Navigation and File Management:

ls: List files and directories in the current directory.
cd: Change the current directory.
pwd: Print the current working directory.
touch: Create an empty file.
mkdir: Create a new directory.
cp: Copy files and directories.
mv: Move or rename files and directories.
rm: Remove files and directories.
File Viewing and Editing:

cat: Display the contents of a file.
more or less: View text files one screen at a time.
nano or vim: Text editors for creating and editing files.
head and tail: Display the beginning or end of a file.
System Information:

hostname: Display or set the system's hostname.
uname: Display system information.
df: Display disk space usage.
free: Display memory usage.
top or htop: Monitor system resource usage in real-time.
User and Group Management:

useradd and userdel: Add and delete user accounts.
passwd: Change user passwords.
groupadd and groupdel: Add and delete groups.
id: Display user and group information.
su or sudo: Switch to the root user or execute commands with superuser privileges.
Package Management:

yum (or dnf on newer versions): Package manager for installing, updating, and removing software packages.
rpm: Command-line package manager for Red Hat-based systems.
Networking:

ifconfig or ip: Display network interface information.
ping: Test network connectivity to a host.
netstat or ss: Display network statistics and connections.
firewall-cmd: Manage the firewall rules (firewalld).
System Control and Services:

systemctl: Control system services and manage the system.
service: Legacy command for managing services.
chkconfig: Configure system services to start at boot.
Process Management:

ps: Display information about running processes.
kill: Terminate processes by PID (Process ID).
pkill and killall: Terminate processes by name.
File Permissions:

chmod: Change file permissions.
chown: Change file ownership.
chgrp: Change group ownership.
Archiving and Compression:

tar: Create and extract tar archives.
zip and unzip: Create and extract zip archives.
gzip and gunzip: Compress and decompress files.
```
![solar-panels](https://github.com/ChesterYuan/Github-doc/assets/56418000/bd0007b1-427a-46b3-9007-203e6757c333)


```terraform

terraform init
```

> When you can, you should apply syntax hightlighting to your codelocks.
> Codeblocks can be used for indicating errors, by adding (bash)



#

```bash
# Define a function that raises an exception
def divide(a, b):
    if b == 0:
        raise ZeroDivisionError("Division by zero is not allowed")
    return a / b

# Call the function with a divisor of zero to raise an error
try:
    result = divide(10, 0)
except ZeroDivisionError as error:
    print(f"An error occurred: {error}")
else:
    print(f"Result: {result}")
```
