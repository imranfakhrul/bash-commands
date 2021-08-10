**List of contents**

1.  [General commands](#general-commands)
2.  [Bash/Terminal related commands](#bashterminal-related-command)
3.  [Permission related commands](#permission-related-commands)
4.  [APT(Package manager) commands](#apt-package-manager-commands)
5.  [Tar commands](#tar-commands)
6.  [Grep commands](#grep-commands)

# General commands

#### ➤ Watch present directory

`pwd`

#### ➤ Watch the files and folders in present directory

`ls`

#### ➤ Navigate directory to back

`cd ..`

#### ➤ Navigate directory to a folder

`cd <folder name>`

#### ➤ Create directory

`mkdir <directory name>`

#### ➤ Create file

`touch <filename>`

#### ➤ Remove/Delete empty directory

`rmdir <directory name>`
`rm -d <directory name>`

#### ➤ Remove/Delete directory that contains data

`rm <directory name>`
`rm -r <directory name>`

#### ➤ Remove/Delete non empty directory without prompt

`rm -rf <directory name>`

<!-- #### ➤ Remove/Delete only directory

`rm -r <directory name>` -->

#### ➤ Know about a command / Mannual of a command

`man <command name>`

#### ➤ Get help about a command

`<command name> --help`

#### ➤ Copy file

`cp <filename> <destination>`

#### ➤ Move file

`mv <filename> <destination>`

#### ➤ Rename file

`mv <filename> <new name>`

#### ➤ Search something from linux file ststem

`locate <file/folder word>`

#### ➤ Search something ignoring case sensitivity

`locate -i <file/folder word>`

#### ➤ Search by multiple words

`locate -i *<word>*<word>`

#### ➤ Write down something into a file

`echo <text> >> <filename>`

#### ➤ Watch the texts of a file

`cat <filename>`

#### ➤ Turn off computer

`sudo halt`

#### ➤ Restart computer

`sudo reboot`

#### ➤ Open "nano"

`nano <filename>`

#### ➤ Open "vim"

`vi <filename>`

#### ➤ Open "jed"

`jed <filename>`

#### ➤ Do something as an administrator

`sudo <command>`

#### ➤ Open administrator command line

`sudo bash`
`su`

#### ➤ Set a root password

`sudo passwd`

#### ➤ Watch available disk space

`df`

#### ➤ Watch available disk space in megabite

`df -m`

#### ➤ Watch the disk usage of all files/folders of system

`du`

#### ➤ Watch the disk usage of a specific folder/file

`df <file/folder name>`

#### ➤ Watch file sizes of all the files of a folder

`ls -lah`

#### ➤ ZIP something

`zip <foldername>`

#### ➤ UNZIP something

`unzip <foldername>`

#### ➤ Get information about system

`uname`

#### ➤ Get detail information about system

`uname -a`

#### ➤ Watch hostname

`hostname`

#### ➤ Watch IP addrees

`hostname -I`

#### ➤ To ping (check internet connection, or check connection to a server)

`ping <server>`

#### ➤ Remove/Delete a file

`rm <filename>`

#### ➤ Remove/Delete multiple files

`rm <filename> <filename> <filename>`

#### ➤ Remove/Delete all file of same extension

`rm *.pdf`

#### ➤ Confirm each file before removing

`rm -i <filename>`

#### ➤ Remove/Delete file without prompt

`rm -f <filename>`

#### ➤ Get interactive root shell

`sudo -i`

#### ➤ Add administrator to run sudo

`sudo adduser <username> sudo`

#### ➤ Enable root account

`sudo passwd root`

#### ➤ Edit sudo configuration

`sudo visudo`

#### ➤ Know date

`date`

#### ➤ Know computer uptime

`uptime`

#### ➤ Read a file

`cat <filename>`

#### ➤ Read multiple file simultaneously

`cat <filename> <filename>`

#### ➤ Analyze a file

`wc <filename>`

#### ➤ See the diffrence btween two files

`diff <filename> <filename>`

#### ➤ Show output text in one line

`less <filename>`

#### ➤ Find and replace text of a file

`sed -i 's/<text to replace>/<text to be replaced>/g' <filename>`

#### ➤ See info of a command

`info <command>`

Ex: `info grep`

#### ➤ See manual of a command

`man <command>`

Ex: `man grep`

#### ➤ To logout

`logout`

#### ➤ To shutdown (must be with root permission)

`shutdown -h now`

#### ➤ To reboot (must be with root permission)

`shutdown -r now`

#### ➤ Get alias list

`alias`

#### ➤ Set an alias

`alias [name="value"]`\
Ex: `alias p="pwd"`

#### ➤ Remove alias from current user alias list

`unalias <alias_name>`

# Bash/Terminal related command

#### ➤ Know your bash version

`bash --version`

#### ➤ Know your bash history

`history`

#### ➤ Add a new environment variable for this session (will be vanished after closing bash)

`export <MYVAR>=<VARVALUE>`

#### ➤ Remove an environment variable from current session

`unset <MYVAR>`

#### ➤ Update current session with changes made in `.bashrc` / `.bash_profile` / `bash.bashrc` / `/etc/profile` file

`source .bashrc`\
`source .bash_profile`\
`source bash.bashrc`\
`source /etc/profile`

#### ➤ Clear terminal window

`clear`

#### ➤ Exit from terminal

`exit`

#### ➤ Search from previous commands

`CTRL + R`

#### ➤ List out all the current session environment variables

`env`

#### ➤ Add directory to $PATH

> Step 1: Add dir to ~/.bash_profile
>
> > `echo 'export PATH="$PATH:[NEW_DIR_LOCATION_TO_ADD_TO_PATH]”’ >> ~/.bash_profile`

> Step 2: Reload to make the changes available to the current shell
>
> > `source ~/.bash_profile`\
> > Or\
> > `. ~/.bash_profile`

> Step 3: Verify that the directory is in the $PATH
>
> > `echo $PATH`

# Permission related commands

#### ➤ Make a file executable

`chmod +x <filename>`

#### ➤ Make a file executable as administrator

`chmod 755 <filename>`

#### ➤ Make a file root executable

`chmod +x <filename>`

# APT (package manager) commands

#### ➤ Install a package

`apt-get <package name>`

#### ➤ Update repository

`apt-get update`

#### ➤ Upgrade system

`apt-get upgrade`

#### ➤ Only upgrade a sinlge package

`apt-get install --only-upgrade <Package Name>`

#### ➤ Upgrade distro

`apt-get dist-upgrade`

#### ➤ Search for a package

`apt-cache search <package name>`

# Tar commands

#### ➤ Create a new tar archive

`tar cvf archive_name.tar dirname/`\
`tar cvfz archive_name.tar.gz dirname/`\
`tar cvfz archive_name.tgz dirname/`\
`tar cvfj archive_name.tar.bz2 dirname/`\
`tar cvfj archive_name.tb2 dirname/`\
`tar cvfj archive_name.tbz dirname/`

**Description**:

| Term | Description                              |
| :--- | :--------------------------------------- |
| c    | Create a new archive                     |
| v    | Verbosely list files which are processed |
| f    | Following is the archive file name       |
| z    | Filter the archive through gzip          |
| j    | Filter the archive through bzip2         |

**NB**:

- `.tgz` is same as `.tar.gz`
- `.tb2` and `.tbz` are same as `.tar.bz2`
- `bzip2` takes more time to compress and decompress than `gzip`. But `bzip2` archival size is less than `gzip`

#### ➤ Extract from an existing tar archive

`tar xvf archive_name.tar`

**Description**:

| Term | Description                |
| :--- | :------------------------- |
| x    | Extract files from archive |

#### ➤ Extract a gzipped tar archive

`tar xvfz archive_name.tar.gz`

#### ➤ Extract a bzipped tar archive

`tar xvfj archive_name.tar.gz`

**NB**:

- In all above commands, `v` is optional

#### ➤ View an existing tar archive

`tar tvf archive_name.tar`

# Grep commands

#### ➤ Search for a given string in a file (case in-sensitive search)

`grep -i "the" demo_file`
