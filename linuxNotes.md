# Linux

### What is linux?
 
Linux is an operating system

* [x] an operating system is a software that manages hardware resources to provide an environment for applications to run

* [x] a linux distribution/distro/flavor is a collection of software and specific application bundled together and shipped as an operating system

* [x] the kernel is the core of OS, it is the intermidiary between the hardware and the software 

### Linux distros

* [x] ubuntu
* [x] redhart
* [x] fedora
* [x] debian
* [x] slackware

### Common lsinux directory 

* [x] / or root : top of the file system hierachy
* [x] /bin      : binaries and executable files
* [x] /etc      : system configuration files
* [x] /home     : home directories
* [x] /opt      : third party software
* [x] /tmp      : temporary directory, cleared on reboot 
* [x] /usr      : user related programs
* [x] /var      : variable data
     
### The shell vrs GUI

* [x] the shell, Command Line Interface(CLI) is the default interface to linux
* [x] the Graphical User Interface(GUI) is a graphical shell
* [x] the CLI is more powerful than the GUI
* [x] server distros do not include GUIs
* [x] desktop distros have both GUIs and CLIs

### The prompt

* [x] displayed when the shell is started
* [x] it gives information such as the username, the linux system you are connected to, current directory etc
* [x] '$' at the end of the prompt indicates you are a normal user
* [x] root shell prompt end with '#'
* [x] '~' represents home or current account's directory


### Root, the superuser

* [x] root or superuser is similar to administrator account in windows, it is all powerful
* [x] normal accounts can only so a subset of the things root can do
* [x] root access is typically restricted to system administrators
* [x] root access maybe required to install, start or stop applications 

### Basic linux commands

* [x] linux commmands are case sensitive
* [x] linux system come with in built documentation
* [x] / is the directory separator in linux
* [x] use backslach(\) to escape spaces

### Enviroment variables

* [x] storage location that have a name and value, typically uppercase
* [x] PATH is an environment variable, it determines the command search path
* [x] contains a list of directories
* [x] how to execute commands outside of $PATH 
	* /full/path/to/command
	* ./command-in-this-dir

### files and directory permissions

* [x] the three main types of permissions are:
		* read(r)
		* write(w)
		* execute(x)	

### permissions - files vs directories

| Permission | File | Directory |
| ---------- | ---- | --------- |
| Read 		 | allows a file to be read  	 | allows the file names in the directory to be read |
| Write 	 | allows a file to be modified  | allows enteries to be modified within the directory |
| Execute 	 | allows the execution of a file | allows access to contents and metadata for entries |

### permission categories

| Symbol | Category | 
| ------ | -------- |
| u		 | user	 	|
| g		 | group 	|
| o		 | other 	|
| a 	 | all	 	|

* [x] every user belongs to at least one group
* [x] users can belong to many groups
* [x] groups are used to organize users
* [x] the `groups` command displays a user's group
* [x] you can use `id -Gn` as a synonym for `groups`

### changing permission(changing mode)
* [x] permissions are also known as modes
* [x] command for changing mode is `chmod`. 
* [x] the mode can be specified using symbolic or numeric notation
* [x] 












