# What is a passwd file?

This a file that stores essential information, which is required during login. In other words, it stores user account information. The /etc/passwd is a plain text file. It contains a list of the system’s accounts, giving for each account some useful information like user ID, group ID, home directory, shell, and more. The /etc/passwd file should have general read permission as many command utilities use it to map user IDs to user names. However, write access to the /etc/passwd must only limit for the superuser/root account. 

# Linux passwd file

$sudo cat /etc/passwd

![](https://github.com/securityinmind365/Passwd/blob/main/passwd.png)


# User enumeration 

Make the file executable

$chmod +x passwdEnum

Run the bash file 

$./passwdEnum

The script will enumerate and list all users from a linux machine 


