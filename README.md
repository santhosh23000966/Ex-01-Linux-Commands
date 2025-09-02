# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

 ![alt text](1.png)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![alt text](2.png)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![alt text](3.png)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![alt text](4.png)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![alt text](5.png)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![alt text](6.png)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![alt text](7.png)


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![alt text](8.png)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![alt text](9.png)

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![alt text](10.png)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![alt text](11.png)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![alt text](12.png)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![alt text](13.png)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![alt text](14.png)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![alt text](15.png)

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![alt text](16.png)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

![alt text](17.png)

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]

 $tar xvzf file.tar *.c

![alt text](18.png)
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![alt text](19.png)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![alt text](20.png)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![alt text](21.png)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name

 $chmod -R 777 /path/to/file/or/folder

![alt text](22.png)
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![alt text](23.png)

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![alt text](24.png)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![alt text](25.png)

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![alt text](26.png)

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![alt text](27(1).png)
![alt text](27(2).png)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![alt text](28.png)
 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![alt text](29.png)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

![alt text](30.png)

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
