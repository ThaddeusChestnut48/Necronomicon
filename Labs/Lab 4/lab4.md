---
Name: Thaddeus Chestnut Jr.
Semester: Fall 22
Course: CSI 106 Linux Fundamentals
---

## Question 1 | Moving around the file system 
* pwd: Print the absolute path of the current working directory; Present Working Directory. 
* cd: Change the shell current working directory; Change Directory.  
* ls: list files inside a given directory; List;

### Using pwd and cd with absolute path (remember to use the bash autocompletion feature)
1. Start a terminal what is your present working directory? 
2. Change your present working directory to `/usr/share/themes`
3. What is your present working directory now? 
4. Change your present working directory to the root of the filesystem
5. Change your present working directory to `/snap/firefox/`
>Take a screenshot of the terminal only. Your screenshot must show all the command that you used to answer questions 1-5.

![q1](q1.png)

### Using pwd and cd with a relative path (remember to use the bash autocompletion feature)
1. Clear your terminal window. Change the working directory to ***YOUR*** home directory. 
2. Change the working directory to the `Downloads` directory.
3. Go back 2 directories. 
4. Where are you now?
5. Change the working directory to the `Documents/` directory.
>Take a screenshot of the terminal only. only. Your screenshot must show all the commands that you used to answer questions 6-10.

![q1.2](q1.2.png)

## Question 2 | The ls command
Download this compressed zip file: lab4files.zip Decompress the zip file in **your home** directory. 
1. Change your present working directory to `/usr/share/`. Using absolute path, list all the files inside the `lab4files` directory. 
2. Change your present working directory to `~/lab4files`. Long list all the files inside your current working directory with human readable file sizes. 
3. Long list all the files inside `lab4files` with human readable file size, and sorted by file size. 
4. Long list all the files inside `lab4files` with human readable file size, sorted by file size. without the user nor the group name, and showing their inode number. 
5. list all the files inside `lab4files` sorted by file extension and in reverse order. 
>Take a screenshot of the terminal only. Your screenshot must show all the commands that you used to answer questions 105. Multiple screenshots may be **required**

![q2.1](q2.1.png)
![q2.2](q2.2.png)
![q2.3](q2.3.png)

## Question 3 | THe tree and exa command
>*The tree and exa commands are not installed by default in Ubuntu. Make sure that the program is installed in your system before you continue with this question. If you are using an earlier version of Ubuntu, Exa is not available in the default repositories. However, you can install it by running this command:*
`curl https://cis106.com/assets/installexa.sh | bash`

1. Using absolute path and having `/etc` as your present working directory. Display a tree of the directory `lab4files`.
2. Change your present working directory to your `Downloads` directory. Display a tree of the directory `lab4files` with the full path prefix for each file, the file permissions, and the file size in human readable format. 
3. Display a tree of the directory `lab4files` sorted by last modified time and showing the file owner and group. 
4. Once you have installed exa, list all the options of the exa command. 
5. Using exa, long list all the files inside `lab4files`
6. Long list `lab4files` showing the header that indicates what each column means. 
7. Long list `lab4files` without the file owner nor group including the header and the date the file was created. 
>Take a screenshot of the terminal only. Your screenshot must show all the commands that you used to answer questions 1-5. Multiple screenshots may be required

![q3.1](q3.1.png)
![q3.2](q3.2.png)
![q3.3](q3.3.png)
![q3.4](q3.4.png)

## Question 4 | Challenge Question 
Use this image as a visual aid during this question
![visualAid](Linux-Filesystem-Incomplete-visual-aid.png)

1. Open a new terminal. What is your present.current working directory 
![4.1](q4.1.png)
2. Change your present/current working directory to the `default` directory located inside `/usr`
![4.2](q4.2.png)
3. Change your present/current working directory to the `ipv4` directory located inside `/proc`
![4.3](q4.3.png)
4. Change you represent/current working directory to the previous present/working directory.
![4.4](q4.4.png)
5. List all the files inside `share/backgrounds` without changing your present working directory.
![4.5](q4.5.png)
6. List all the files inside your `cis106` directory located in YOUR home directory.
![4.6.1](q4.6.1.png)
![4.6.2](q4.6.2.png)
![4.6.3](q4.6.3.png)
7. List all the files inside your `Downloads` directory. Your present working directory has to be `/home` before your can list all the files.
![4.7](q4.7.png)
8. Change your present/current working directory to `disk/by-id` and from there long list all the files in your home directory including hidden files.
![4.8](q4.8.png)
9.  List all the files sorted by modification time inside the `share/themes` directory.
![4.9](q4.9.png)
List all the files sorted by file extension inside the /usr/share directory.
![4.10.1](q4.10.1.png)
![4.10.2](q4.10.2.png)
![4.10.3](q4.10.3.png)
![4.10.4](q4.10.4.png)
![4.10.5](q4.10.5.png)
![4.10.6](q4.10.6.png)
