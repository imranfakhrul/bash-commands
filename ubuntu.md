
## Watch present directory

`pwd`

## Watch the files and folders in present directory

`ls`

## Navigate directory to back

`cd ..`

## Navigate directory to a folder

`cd <folder name>`

## Create directory

`mkdir <directory name>`

## Create file

`touch <filename>`

## Remove/Delete empty directory

`rmdir <directory name>`
`rm -d <directory name>`

## Remove/Delete directory that contains data

`rm <directory name>`
`rm -r <directory name>`

## Remove/Delete non empty directory without prompt

`rm -rf <directory name>`

<!-- ## Remove/Delete only directory

`rm -r <directory name>` -->

## Know about a command / Mannual of a command

`man <command name>`

## Get help about a command

`<command name> --help`

## Copy file

`cp <filename> <destination>`

## Move file

`mv <filename> <destination>`

## Rename file

`mv <filename> <new name>`

## Search something from linux file ststem

`locate <file/folder word>`

## Search something ignoring case sensitivity

`locate -i <file/folder word>`

## Search by multiple words

`locate -i *<word>*<word>`

## Write down something into a file

`echo <text> >> <filename>`

## Watch the texts of a file

`cat <filename>`

## Clear terminal window

`clear`

## Exit from terminal

`exit`

## Turn off computer

`sudo halt`

## Restart computer

`sudo reboot`

## Open "nano"

`nan <filename>`

## Open "vim"

`vim <filename>`

## Open "jed"

`jed <filename>`

## Do something as an administrator

`sudo <command>`

## Open administrator command line

`sudo bash`
`su`

## Set a root password

`sudo passwd`

## Watch available disk space

`df`

## Watch available disk space in megabite

`df -m`

## Watch the disk usage of all files/folders of system 

`du`

## Watch the disk usage of a specific folder/file

`df <file/folder name>`

## Watch file sizes of all the files of a folder

`ls -lah`

## Create a .tar archive

`tar -cvf`

## Untar a .tar archive

`tar -xvf`

## Watch the list of the content of a .tar archive

`tar -tvf`

## ZIP something

`zip <foldername>`

## UNZIP something

`unzip <foldername>`

## Get information about system

`uname`

## Get detail information about system

`uname -a`

## Install a package

`sudo apt-get <package name>`

## Update repository

`sudo apt-get update`

## Upgrade system

`sudo apt-get upgrade`

### Only upgrade a sinlge package
`sudo apt-get install --only-upgrade  <Package Name>`

## Upgrade distro

`sudo apt-get dist-upgrade`

## Search for a package

`apt-cache search <package name>`

## Make a file executable

`chmod +x <filename>`

## Make a file executable as administrator

`chmod 755 <filename>`

## Make a file root executable

`sudo chmod +x <filename>`

## Watch hostname

`hostname`

## Watch IP addrees

`hostname -I`

## To ping (check internet connection, or check connection to a server)

`ping <server>`

## Remove/Delete a file

`rm <filename>`

## Remove/Delete multiple files

`rm <filename> <filename> <filename>`

## Remove/Delete all file of same extension

`rm *.pdf`

## Confirm each file before removing

`rm -i <filename>`

## Remove/Delete file without prompt

`rm -f <filename>`

## Get interactive root shell

`sudo -i`

## Add administrator to run sudo

`sudo adduser <username> sudo`

## Enable root account 

`sudo passwd root`

## Edit sudo configuration

`sudo visudo`

## Know date

`date`

## Know your hostname

`hostname`

## Know your bash version

`bash --version`

## Know your bash history

`history`

## Know computer uptime

`uptime`

## Search from previous commands

`CTRL + R`

## Read a file

`cat <filename>`

## Read multiple file simultaneously

`cat <filename> <filename>`

## Analyze a file

`wc <filename>`

## See the diffrence btween two files

`diff <filename> <filename>`

## Show output text in one line

`less <filename>`