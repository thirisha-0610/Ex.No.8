# 19CS545-Ex8 - Create a user account in GitHub
### Name:Thirisha A
### Reg no:212223040228
# AIM:
To create a Repository

# Procedure:

1. grep "home" /etc/passwd: This command u lizes the grep u lity, which stands for 
“global regular expression print.” It searches for the text “home” within the /etc/passwd file. 
Now, let’s break down what each part of this command does: 
◦ grep: The command itself. 
◦ "home": The search pa ern enclosed in double quotes. In this case, we’re looking 
for lines containing the word “home.” 
◦ /etc/passwd: The file we’re searching within. The /etc/passwd file is a cri cal 
system file on Unix-like systems that stores informa on about user accounts. Each 
line in this file represents a user and contains details such as the username, user ID 
(UID), home directory, and default shell. 
◦ When you run this command, it scans through the /etc/passwd file and displays 
any lines that match the search pa ern (i.e., lines containing “home”). Typically, 
these lines correspond to user accounts and their associated home directories. 
2. grep "home" /etc/passwd > /root/search.txt: This command builds upon the 
previous one but adds a redirec on step. Let’s break it down: 
>: The greater-than symbol is used for output redirec on. It takes the output produced by the 
grep command and saves it to a file. 
/root/search.txt: The target file where the output will be stored. In this case, it’s a file 
named search.txt located in the /root directory. 
So, instead of displaying the matching lines on the screen, this command redirects them to the 
specified file. If you examine the contents of search.txt, you’ll find the same informa on as 
displayed by the ini al grep command.

# Output:
![image](https://github.com/user-attachments/assets/36643243-54fe-4ff9-8ad9-399c1514c1c0)
# Result:

Thus a Repository has been created successfully.
