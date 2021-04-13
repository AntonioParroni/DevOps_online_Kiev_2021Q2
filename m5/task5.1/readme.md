### Linux 

## Task1.Part1
I had some difficulties with CentOS7. With Yum update process and DNF.

  ![alt text](images/1.jpg)

So now I am using a simple Ubuntu Server 20.04 with Gnome.

![alt text](images/2.png)
# 1) Log in to the system as root.

  ![alt text](images/3.png)

# 2) Use the passwd command to change the password. Examine the basic parameters of the command. What system file does it change *?

  ![alt text](images/5.png)

  ![alt text](images/4.png)

# 3) Determine the users registered in the system, as well as what commands they execute. What additional information can be gleaned from the command execution?

  We can use the command ``` who ``` to see the list of active users.
    ![alt text](images/6.png) 

  While can also use the ``` cat /etc/passwd ``` or ``` getent passwd ``` in order to get all the users present in our system.
   ![alt text](images/7.png)

   - What additional information can be gleaned from the command execution?
   
   We can see, that some of the applications/processes have their own user with respective policy.

# 4) Change personal information about yourself.

![alt text](images/8.png)
![alt text](images/9.png)
We can also change the user's username with ``` usermod ``` command.

# 5) Become familiar with the Linux help system and the man and info commands. Get help on the previously discussed commands, define and describe any two keys for these commands. Give examples.
``` man man ``` ;)
![alt text](images/10.png)

![alt text](images/11.png)
- ```passwd -d``` or ```passwd --delete``` 

  We can delete the selected user's password and make it empty.

- ```passwd -S``` or ```passwd --status``` 

  Display detailed information about users's password. 

P.S. My personal favorite key/flag is```--verbose``` :D

# 6) Explore the more and less commands using the help system. View the contents of files .bash* using commands.

![alt text](images/14.png)
![alt text](images/12.png)
![alt text](images/13.png)


# 7) * Describe in plans that you are working on laboratory work 1. Tip: You should read the documentation for the finger command.

![alt text](images/15.png)
We've been studying some basic Linux users administration and managment tools.

# 8) * List the contents of the home directory using the ls command, define its files and directories. Hint: Use the help system to familiarize yourself with the ls command.

![alt text](images/16.png)

## Task1.Part2
# 1) Examine the tree command. Master the technique of applying a template, for example, display all files that contain a character c, or files that contain a specific sequence of characters. List subdirectories of the root directory up to and including the second nesting level.

![alt text](images/17.png) 
- Display all files that contain a character c
![alt text](images/18.png) 
- List subdirectories of the root directory up to and including the second nesting level.
![alt text](images/19.png) 

# 2) What command can be used to determine the type of file (for example, text or binary)? Give an example.

![alt text](images/20.png) 


# 3) Master the skills of navigating the file system using relative and absolute paths. How can you go back to your home directory from anywhere in the filesystem?

![alt text](images/21.png) 

# 4) Become familiar with the various options for the ls command. Give examples of listing directories using different keys. Explain the information displayed on the terminal using the -l and -a switches.

![alt text](images/22.png) 

# 5) Perform the following sequence of operations:
- create a subdirectory in the home directory;
- in this subdirectory create a file containing information about directories
located in the root directory (using I/O redirection operations);
- view the created file;
- copy the created file to your home directory using relative and absolute
addressing.
- delete the previously created subdirectory with the file requesting removal;
- delete the file copied to the home directory.



# 6) Perform the following sequence of operations:
- create a subdirectory test in the home directory;
- copy the .bash_history file to this directory while changing its name to
labwork2;
- create a hard and soft link to the labwork2 file in the test subdirectory;
- how to define soft and hard link, what do these
concepts;
- change the data by opening a symbolic link. What changes will happen and
why
- rename the hard link file to hard_lnk_labwork2;
- rename the soft link file to symb_lnk_labwork2 file;
- then delete the labwork2. What changes have occurred and why?



# 7) Using the locate utility, find all files that contain the squid and traceroute sequence.



# 8) Determine which partitions are mounted in the system, as well as the types of these partitions.



# 9) Count the number of lines containing a given sequence of characters in a given file.



# 10) Using the find command, find all files in the /etc directory containing the host character sequence.



# 11) List all objects in /etc that contain the ss character sequence. How can I duplicate a similar command using a bunch of grep?



# 12) Organize a screen-by-screen print of the contents of the /etc directory. Hint: You must use stream redirection operations.



# 13) What are the types of devices and how to determine the type of device? Give examples.



# 14) How to determine the type of file in the system, what types of files are there?



# 15) * List the first 5 directory files that were recently accessed in the /etc directory.
