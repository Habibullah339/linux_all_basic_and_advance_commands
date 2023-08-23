# linux_all_basic_and_advance_commands
List all the files and directories in present directory with different flags
```bash
  ls
```
```bash
  ls -l
```
```bash
  ls -a
```
Change Directory for moving between directories
```bash
  cd <dir name>
```
```bash
  cd ..
```
```bash
  cd ./your/location/where/want/to/move
```
Current Working directory
```bash
  pwd
```
Check User who is loggedin
```bash
  whoami
```
```bash
  users
```
Clear the terminal
```bash
  clear
```
Exit the terminal
```bash
  exit
```
Shutdown from terminal
```bash
  init 0
```
Restart from terminal
```bash
  init 6
```
Login as root user
```bash
  sudo -i
```
Create Directory
```bash
  mkdir <dir_name>
```
Remove Directory
```bash
  rmdir <dir_name>
```
Create blank file
```bash
  touch <file_name>
```
Remove File
```bash
  rm <file_name>
```
```bash
  rm -f <file_name>
```
Editors to create and edit scripts and files
```bash
  nano <file_name>
```
```bash
  vi <file_name>
```
View the content of file
```bash
  cat <file_name>
```
```bash
  cat <file_name> head
```
```bash
  cat <file_name> tail
```
Changing permissions of files and changing permission groups and owner group
```bash
  chmod +x <file_name>
```
```bash
  chmod +R <file_name>
```
```bash
  chmod +W <file_name>  
```
```bash
  chmod 775 <file_name>
```
```bash
  chgrp +x <file_name>
```
```bash
  chown +x <file_name>
```
Word count and line count in a file 
```bash
  wc <file_name>
```
```bash
  wc -l
```
Copy Files
```bash
  cp [file in source dir] [destination dir]
```
Rename Files and Directories
```bash
  mv <current_name> <new_name>
```
Process managemnt display processes and display usage and killing processes
```bash
  ps
```
```bash
  ps aux
```
```bash
  top
```
```bash
  htop
```
```bash
  btop
```
```bash
  kill <process_id>
```
```bash
  killall
```
Networking, connectivity ip addresses and downloading files
```bash
  ping <hostname>
```
```bash
  ifconfig
```
```bash
  netstat <hostname>
```
```bash
  wget <url>
```
Package maangement in Linux
```bash
  apt-get install <package_name>
```
```bash
  apt-get update 
```
Monitoring linux systema like checking disk usage
```bash
  du
```
```bash
  df
```
```bash
  free
```
User Managment in Linux like creating user updating passwords
```bash
  useradd
```
```bash
  userdel
```
```bash
  passwd
```
Advance files Manipulation
```bash
  grep
```
```bash
  awk
```
```bash
  sed
```
