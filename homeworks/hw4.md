Homework: 4 The Linux Filesystem
Watch the video “Linux Filesystem Explained” and read the presentation “How to navigate the filesystem” then answer the questions below.

1 Explain the difference between absolute path and relative path:
a relative path points to a specific location in a file system but absolute path refers to the same location in a file system relative to the root directory


2 Why Linux uses / instead of \ for its directory paths?


3 In Windows, these files are all the same: File FILE file and FiLE. But in Linux this is not the case, Why?

windows file system is not case sensitive but Linux treats capital and lower-case letters as different characters.

4 What is the Filesystem Hierarchy Standard (FHS) and who maintains it?

The Filesystem Hierarchy Standard (FHS) defines the directory structure and directory contents in Linux distributions and it is maintained by the Linux Foundation.

5 Explain what type of files are stored in the following directories:

Directory|What is it used for
--|--|
/bin|Contains binary commands that can be used by system admins,users and scripts.
/dev|Contains device files, such as cd/dvd
/etc|Contains static config files which are local.
/home|Optional directory that might not exists in all linux distros
/lib|Contains shared libraries that are loaded when a program is run.
/opt|Contains static shareable add-on software packages.
/tmp|Contains temporary files.
/var|Contains variable data files.
/proc|Contains all the details about Linux system including configuration parameters,processes
/usr|Contains shareable, read-only applications and files.


6 How does a period at the beginning of a file name means (example .bashrc)?

. means file is hidden 

7 Which command would you use to list all the files inside the /usr/share/ directory?

ls -a /usr/share/

8 If you are working in the /usr/share/icons directory and want to move to your home directory, which command would you use?
 
cd 


9 Explain what these commands do:

cd .config/.htop; cd ../; ls -lX

move to htop dir inside cofig dir then move one dir back and list all the files inside the dir by long list and sort it by entry extntions from a-z 


John has a lot of files in the directory /var/www/html/webapp. He wants to long list all the files, including hidden files, by modification time (newest first), and with human-readable file sizes. Which command should he use conjuring that his current working directory is:
/home/john/.git/

ls -laht /var/www/html/webapp