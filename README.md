# Linux notes
It's old version is UNIX, likewise windows old version is DOS. it's development is related 1960-70

# UNIX
Developed in 1960's and 70's at AT&T Bell Labs by Ken Thompson, Dennis Ritchie, and others.
Designed as a portable, multi-tasking, and multi-user system.
- The source code was proprietary, although it had many variants, including BSD ( Berkeley Software Distribution) and commercial version like AIX, HP-UX and Server environments.
- Historically dominant in academic, enterprise, and Server enverionments.
- Popular variants includes IBM AIX, HP-UX and Orcale solaris.

# Linux
  Created by Linus Torevalds in 1991, inspired by the Unix system but not directly derived from its code.
  It is an open-source operating system Kernel licenced under the GNU General Public Licence (GPL).

     Win=user > Application > OS > Hardware
     Linux=user > Shell > kernel > Hardware

  Shell is outer layer of anything, Outer surface of Linux with this we operate Linux.
  Shell word come from that water shell 🐚 which have pearl inside.

  Technically shell is user interface of linux, when we have to control it so we use shell. Number of shells comes in Linux that we can use , for other 
  purposes we have different shells here.

# Functions of Operating System

1) Process Management
2) Memory Management- RAM and harddrive primary and secondary memory here we are talking about.
3) File system mangement- Windows have NTFS and FAT. Linux have EXT2, EXT3, EXT4, XF5.
4) Device Management- OS not directly manage the hardware but wirh help of Kernel it to, kernel is in both windows and Linux, kernel interact the hardware same on both. Kernel is a part of OS. In here first Drivers and then Kernels.
5) Security and Protection
6) User Interface
7) Network Management
8) System Performance Monitoring
9) Utilities and Support services

# Features of Linux

1) Open Source -> Linux is licensed under the GNU General Public license ( GPL ), Which allows users to freely use,  modify and distribute the software, The source code is accessible to everyone( This are  those softwares which are published with the source code, whiich anyone can take, use and modify. Like we made a program on C language that difference odd and even numbers when we comply that, an binary is generate, If we share that binary then it's closed source, On the other hand if we share the program that we wrote then it's open source,  Which user can customise accordingly by there requirements. This Linux OS is fully open source, we can freely customise or modify it and published it by our name, but if we use that financially so the profit that generate we have to share it and gave referance of source. Like this OS is made on that particular OS source code , that License have it's term and conditions according to that we have follow it.
   
2) Multitasking -> Linux can handle multiple tasks simultaneously without degrading performance, making it ideal for both personal and enterprise-level applications.

3) Multi-user Support -> Multiple users can access and work on a Linux system simultaneously without interfering  with each other.

4) Probability -> Linux is highly portable and can run on a variety of ahrdware platforms, from servers and desktops to embedded and smartphones.

5) Security -> Linux is designed with robust security features, including file permissions, user authentication, and a strong firewall. It is less prone to malware compared to other operating systems.

6) Customisation -> Users can customise Linux to meet their needs by choosing from a variety of distributions ( like Ubuntu, fedora or Debian ) and desktop enverionments ( like GNOME, KDE or XFCE ).

7) Command-Line Interface ( CLI ) -> The Linux terminal offers a rich command-line interface, enabling users to perform complex tasks efficiently through scripting and commands.

8) Stability and Performance -> Linux is known for itd stability, often running for years without requiring a reboot. It is also efficient in resource usage, making it suitable for high-performance computing.

9) package Management -> Linux distributions use package managers ( like apt, yum or pacman ) tp simplify the installation,  updating, and removal of software.

10) community Support -> Linux has a large and active community of deveelopers and users who provide support, tutorials, and documents.

11) Free of Cost -> Most Linux dsitributions are free to download and use,  reducing costs for personal users and organisations.


# Linux Distributions






# CentOS Installation





# Directory Structure of Linux




# Remmote Shell
   
# Basic Commands 
 1. hostname :  Hostname is used to display the system's DNS name, and to display or set its hostname or NIS domain name.
 2. pwd (present working directorie) : Print the full filename of the current working directory.
 3. id : Print user and group information for each specified USER, or (when USER omitted) for the current user.
 4. ls : List information about the FILEs (the current directory by default).Sort entries alphabetically if none of -cftuvSUX nor --sort is specified.
        Mandatory arguments to long options are mandatory for short options too.
        ls -l : single vertical list.
        ls -h , --human-readable : 
        ls -a , --all : 
        ls -R :
        ls -t : 
 5. cd(Change directory)  : home of that user and if that user dont have its home directory then it deny i dont have home.  
                    cd .  : shows the current directory.   
                    cd .. : one folder out from the location.        
 6. Switches or Subcommands : 
             a) -h,--help,help : it will give summarised information theoritically of commmands switches.      
             b) man : man is the system's manual pager.  Each page argument given to man is normally the name of a program, utility or function.  The manual page asso‐
             ciated with each of these arguments is then found and displayed.  A section, if provided, will direct man to look only in  that  section  of  the
             manual.The  default  action  is  to search in all of the available sections following a pre-defined order (see DEFAULTS), and to show only the
             first page found, even if page exists in several sections ( for more practical information of commands switches).                      
       c) info : it have both practical and theoritical info of commands switches.
 7. ifconfig :  Ifconfig is used to configure the kernel-resident network interfaces.  It is used at boot time to set up interfaces as necessary.  After that, it
               is usually only needed when debugging or when system tuning is needed. If no arguments are given, ifconfig displays the status of the currently active interfaces.  If a single 
               interface argument is given, it displays the  status  of  the  given interface only; if a single -a argument is given, it displays the status of all interfaces, even those that 
               are down.       
           ifconfig -a :  display all interfaces which are currently available, even if down.   
           ifconfig -s :  display a short list (like netstat -i).     
           ifconfig -v :  be more verbose for some error conditions.
  8. touch : create an empty file at the present location, example.
           [root@localhost Desktop]# touch file.txt
           [root@localhost Desktop]# ls
           file.txt
       -  we can create mutiple files with by space between and there name like this,
         [root@localhost Desktop]# touch f1.txt f2.txt f3 f4
         [root@localhost Desktop]# ls
         f1.txt  f2.txt  f3  f4
       - and if we want to create a file by name which have space we can by naming it in double,single qoutes (" ") or can use backslash\ before the space like this,
        double qoutes - [root@localhost Desktop]# touch "varin local"
                        [root@localhost Desktop]# ls
                        'varin local'
        single qoutes - [root@localhost Desktop]# touch 'vc 2'
                        [root@localhost Desktop]# ls
                        'vc 2'
         Backslash - [root@localhost Desktop]# touch vc\ 3
                     [root@localhost Desktop]# ls
                      'vc 3'
9. file : describes the media type of file, example.
           [root@localhost Desktop]# file file.txt
           file.txt: empty

10. cat : to read the files we use cat commands and also to write content in the file like this,
          [root@localhost Desktop]# cat d1
          [root@localhost Desktop]# cat > d1
          this is for test purpose.
          ^C
          [root@localhost Desktop]# cat d1
          this is for test purpose.

         important : cat <<EOF>> test.txt (this is basically used when we out of the file after saving content)
    
12. mkdir : to create a directory we use mkdir command, example.
            [root@localhost Desktop]# mkdir dir1 dir2 dir3 dir4
            [root@localhost Desktop]# ls
            d1  d2  dir1  dir2  dir3  dir4
            when we have to create directory which'll have sub directories or folder we can create it by using switch -p which look like this,
           [root@localhost Desktop]# mkdir -p s1/s2/s3/s4
           [root@localhost Desktop]# ls -R s1/
           s1/:
           s2
           s1/s2:
           s3
           s1/s2/s3:
           s4
           s1/s2/s3/s4:
13. rmdir : this is only use to remove the files.
14.    rm : use to remove the files and directory we use rm command.
       example :
            rm : remove file.
         rm -r : recursively removes a directory and its contents.
         rm -f : forces the removal of files without prompting for confirmation.
         rm -rf : it use to remove directories and their contents withot any condirmation.
         rm -v : shows details of what is being removed.
15. Redirecion ( > ) : redirect the output to a file or subfile.
16. pipe ( | ) : pass the output of one command as input of another command.
17. echo " ", ' ' : the echo command in Linux is used to display a line of text or a variable's value to the terminal.
18. wildcard : *  = any number or characters (incl zero)            ca*         car,ca,carpet
               ?  = single character                                hel?        help,hell,helw
               [] = single character from range                     file[0-2]   file0,file1,file2
                                                                    [hd]ello    hello or dello
               [!] = single character file not listed in bracket    file[!1]    file2, file3
               { } = ccomma separated terms                         {*.txt,*.pdf}  hello.txt, doc.txt, source.pdf
19. cp :
20. mv :
    
# Text Editor

- Linux offers various text editors for editing connfiguration files, writing code, or managing text files. 
1. Command-line text editors

-  Vi/Vim
  
-  Features:
    - Modes: insert, Command, Visual.
    - Lightweight, available on almost all Linux systems.
    - syntax heighlighting and plugin support (Vim).
-  Basic Commands:
    - Insert mode: Press i.
    - Save: :w.
    - Exit: :q.
    - Force exit without saving: :q! .
    - exit with saving: :wq!.
-  nano
  - Features:
     - User-friendly and Simmple.
     - Display of shortcuts at the bottom.
  - Basic Commands:
     - Ctrl+O: Save file.
     - Ctrl+X: Exit editor.
     - Ctrl+k: Cut text.
     - Ctrl+U: Paste text.
-  Cat 
  - cat is also use as a text editor but it is not use for big files.
  - this is basically use to read the the content.

# Compression Tools

1. bzip2 : bzip2 messages (file name)
2. gzip  : gzip messages1
3. zip   : zip messages2.zip messages2  (create new file)
4. 7za   : 7za a messages3.7z messages3  (compress more compare others) (create new file)
           7za e messages3.7z
6. tar   : tar -cvf messages4.tar messages4 
           tar -xvf messages4.tar
           tar -czvf messages5.tgz messages5
           tar -cjvf messages6.tbz messages6

# String Processing

1. Sort : The sort command is used to arrange the lines of a text file or input in a specified order, either alphabetically or numerically, ascending or descending.
 
* Common Options:
  
    -n : Sort numerically (default is lexicographically).
  
    -r : Reverse the sort order (descending).
  
    -k : Sort based on a specific field or column.
  
    -u : Eliminate duplicate lines.
  
    -t : Specify a delimiter (default is whitespace).
  
    -f : Ignore case (case-insensitive sorting).
  
    -b : Ignore leading blanks.
  
    -M : Sort by month names (e.g., "Jan", "Feb", "Mar").
  
    -o : Write the sorted output to a file.

2. head :
3. tail :
4. wc (word count) :
5. cut :
6. paste :
7. grep :


# User Group Management

 A user account in linux is a record that allows an individual or process to log in and access the system with specific permissions and privileges. It erves as an identitiy for users to interact with the system, ensuring security and accountability.

* Key components of a User Account

   Username: A unique identifier for the user on the system (e.g., sachin, admin).
   
   User ID (UID): A unique numerical ID assigned to each user. for example:
   
       - 0 is reserved for the root user.
       - UIDs above a certain range are for regular users.
   Group ID (GID): Specifies the primary group the user belongs to. groups help manage 
   permissions collectively.

   Home Directory: A personal directory for the user to store files and configuration 
   settings (e.g., /home/username).

   Shell: The default command-line interpreter for the user (e.g., /bin/bash).

   Password: Stored (usually in an encrypted format) to authenticate the user. It's 
   often managed in /etc/shadow.

   System Files: 

            /etc/passwd: Contains user account information (excluding passwords).
            /etc/shadow: Stores encrypted password data.

* Types of User Accounts

    System Accounts: Used by system services and processes (e.g., root, daemon).

    Regular User Accounts: Created for individuals to log in and perform tsaks.

    Service Accounts: Dedicated accounts for applications or services to run with 
    specific permissions.
  
* Importance of User Accounts

     Security: ensures that only authorised individuals or processes access resources.

     Acccountability: Tracks user actions and access logs.

     Customization: Allows personalised settings for each user.

In Linux, managing user accounts involves creating, modifying, and deleting them using commands like useradd, usermod, and userdel, or by directlyediting configuration files with administrative privileges.

* Key Features of a Group

     Group Name: A Unique identifier for the group (e.g., developers, admin).

     Group ID (GID): A Unique numerical identifier assigned to each group.

     Group Members: A list of users who belong to the group. A user can beloong to multiple groups.

     Primary Group: Each user is assigned a primary group when their account is created. Files created by the user are associated with this grouups.

* Types of Groups

     System Groups: Used by system services and processes (e.g., adm,daemon).

     User Groups: Created for users to belong tp specific roles or teams (e.g., dev,marketing).

* Benefits of Using Groups

     Access Control: Allows collective permisssion management for files, directories and resources.

     Simplified Administration: Reduces the complexity of managing permissions for multiple users.

     Collaboration: Faciltates teamwork by providing shared access to resources.

          # cat /etc/login.defs
          # grep -v "^#" /etc/login.defs | grep -v "^$"


# System Files Linux

Passwd File

   * cat /etc/passwd

         [User]    :[x]   :[UID]   :[Comment]                :[Home directory]          :[Default shell]
         root      :x     :0       :root                     :/root                     :/bin/bash
         daemon    :x     :2       :daemon                   :/sbin                     :/sbin/nologin
         sshd      :x     :74      :privilege-sperated SSD   :/usr/share/empty.sshd     :/usr/sbin/nologin
         apache    :x     :48      :apache                   :/usr/share/httpd          :sbin/nologin
         armour    :x     :1000    :Armour Infosec           :/home/armour              :/bin/bash
      
      1. root        -   The first root is the username.
      2. x           -   Indicates that the account is protected by a shadowed password
      3. 0           -   0 is the suer ID for this user.
      4. 0           -   0 is the group ID for this user.
      5. root        -   comment about this user.
      6. /root       -   /root is the home directory for this user.
      7. /bin/bash   -   And finally /bin/bash is the shell for this user.


  Shadow File
    * cat /etc/shadow

          [User]   :[Encrypted Password]  :[Last pass change]  :[Min pass age]  :[Max pass age]   :[Warning period] :[Inact period]  :[Exp date] :[Unused]

  adcdd
          
