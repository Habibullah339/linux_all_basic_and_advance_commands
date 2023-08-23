# linux_all_basic_and_advance_commands
List all the files and directories in present directory with different flags
```bash
  ls #list the files
```
```bash
  ls -l #List fiels with more information like permissions info
```
```bash
  ls -a #List the hidden files also with additional info
```
Change Directory for moving between directories
```bash
  cd <dir name> #Change the directory
```
```bash
  cd .. #Change directory to previous directory
```
```bash
  cd ./your/location/where/want/to/move
```
Current Working directory
```bash
  pwd #Display the current working Directory 
```
Check User who is loggedin
```bash
  whoami #Display the user loggedin
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
  nano <file_name> #linux comand line file editor
```
```bash
  vi <file_name> #Linux command line file editor
```
View the content of file
```bash
  cat <file_name> 
```
```bash
  cat <file_name> head #Display the head of file means starting of file
```
```bash
  cat <file_name> tail #Display the end of file
```
Changing permissions of files and changing permission groups and owner group
```bash
  chmod +x <file_name> #Add the execute permissions 
```
```bash
  chmod +R <file_name> # Add the Read permissions to file
```
```bash
  chmod +W <file_name>  #Add the Write permissions to file
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
  wc -l #Display the number of lines in file 
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
  ps #Display info about runing processes with there ids
```
```bash
  ps aux
```
```bash
  top #Display the system usage and proceses
```
```bash
  htop
```
```bash
  btop
```
```bash
  kill <process_id> #kill process by using process id 
```
```bash
  killall
```
Networking, connectivity ip addresses and downloading files
```bash
  ping <hostname> #The icmp ping process used to check the availability of host
```
```bash
  ifconfig #Configure network information like ipaddress
```
```bash
  netstat <hostname>
```
```bash
  nslookup
```
```bash
  traceout
```
```bash
  wget <url> #Download files from internet
```
Package maangement in Linux
```bash
  apt-get install <package_name> #Install packages in your system
```
```bash
  apt-get update #Update the pckages list in your system
```
Monitoring linux systema like checking disk usage
```bash
  du #display the disk usage of directory 
```
```bash
  df #display the disk usage fo file system
```
```bash
  free
```
User Managment in Linux like creating user updating passwords
```bash
  useradd #Create a new user in linux
```
```bash
  userdel #Delet a already created user
```
```bash
  passwd #Change password of user
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
File compression and archiving 
```bash
  tar
```
```bash
  gzip
```
```bash
  unzip
```
Shell Scripting special variables
```bash
  $0  #Displays he name of the file
```
```bash
  $1..$n #Positional aurguments we pass when we run scrip
```
```bash
  $# #Displays the total number of aurguments 
```
```bash
  $* #Display al positional aurguments in single line
```
```bash
  $? #Displays the exit status of last command 
```
```bash
  $$ Displays the process ID
```
```bash
  $HOME
```
```bash
  $PWD
```
```bash
  $USER
```
