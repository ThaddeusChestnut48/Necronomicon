---
Name: Thaddeus Omar Chestnut Jr.
Date: Dec. 14 2022
Course: CIS 106 Linux Fundamentals
---
## Question 1
For every command in this list, including the following:
>Description 
Formula
3 Examples

* awk 
The
* cat
The cat command allow someone to read an entire text or a specific number of lines.

Formula: 
cat + option + file(s) to display

Examples:
`cat todo.lst`
`cat  ~/Documents/todo.lst`
`cat -b ~/Documents/todo.md`

* cp
The cp command copies a file.

Formula :
cp + files to copy + destination

Examples:
`cp todo.lst ~/Downloads/photos`
`cp todo.lst`
`cp -r + cis106f22 + home/tchestnut44967`

* cut
This can cut certain elements of a text file, so only specific fields are seen.

Formula: 
cut + option + file(s)

Example:
`cut -d ':' -f1 /etc/passwd`
`cut -d ':' -f1,7 /etc/passwd`
`cut -d ':' --output-delimiter=' => ' /etc/passwd`
* grep
The grep command can grab specified elements of a text file.

Formula:
grep + option + search criteria + file(s)

Examples
`grep 'dracula' ~/Documents/dracula.txt`
`grep -in 'dracula' ~/Documents/Books/dracula.txt`
`grep -n '^d...' ~/Documents/Books/dracula.txt`

* head
This command shows the first 10 lines of a text file.

Formula:
head + option + file(s)

Examples:
`head ~/Documents/Book/dracula.txt`
`head -5 ~/Documents/Book/dracula.txt`
`head -3 ~/Documents/Book/dracula.txt`

* ls
The ls command lists all files and sub0directories within a directory

Formula:
ls + option + directory to list

Examples:
`ls cis106f22`
`ls ~/Documents`
`ls ~/Downloads/pictures`

Description:
* man
The man command shows a manuel of what the command does and its options.

Formula:
man + command

Examples:
`man ls`
`man cp`
`man awk`

* mkdir
The command creates a directory where files can be placed

Formula: 
mkdir + the name of the directory 

Examples:
`mkdir wallpapers`
`mkdir wallpapers/ocean`
`mkdir wallpapers/new\ cars`

* mv
The mv command can move files using absolute pathways; it can also change the name of said file.

Formula: 
mv + source + destination

Examples: 
`mv hello.md hi.md`
`mv Downloads/homework.pdf Documents/`
`mv games/ wallpapers/ /media/student/flashdrive/`

* tac
This command acts the same as the cat command but shows the text file bottom to top.

Formula: 
tac + option + file(s) to display

Examples:
`tac todo.lst`
`tac  ~/Documents/todo.lst`
`tac -b ~/Documents/todo.md`

* tail
The tail command shows the last 10 lines of a text file. 

Formula:
tail + option + file(s)

Examples:
`tail ~/Documents/Book/dracula.txt`
`tail -5 ~/Documents/Book/dracula.txt`
`tail -3 ~/Documents/Book/dracula.txt`

* touch
The touch command creates files within any place given a absolute path or relative path; although I personally like absolute path.

Formula:
touch + filename 

Example: 
`touch list`
`touch list_of_cars.txt script.py`
`touch ~/Downloads/games.txt`

* tr
The tr command translates or deletes certain characters in a text file. Great for programming.

Formula:
Standard output | tr + option + set + set 

Examples: 
`cat file.txt | tr '.' ','`
`cat file.py | tr -s "[:space:]" '\t'`

* tree
The tree command shows a listing branch list from the initial position given the present working directory. From there it gives all sub-directories and their files.

Formula:
tree + options + directory

Examples:
`tree cis106f22`

* vim/nano
This is a text editing station where people can can change text files from within the terminal.

Formula: 
vim + option + document

Example:
`vim ~/Documents/work.txt`
`vim work.txt`
`vim -b work.txt`


## Question 2
### Answer each question
* How to work with multiple terminals open? 
You can work with multiple terminals by clicking the add part on the left hand side of the terminal.
* How to work with manual pages? 
Always add man to the command that you are using or you can add a --help, an example being:
`man ls`
`ls --help`
* How to parse (search) for specific words in the manual page
* You can parse for specific words in the manual page by using grep while piping after the man command.
`man ls | grep "long list"`
* how to redirect output `(> and |)` 
We can redirect outputs to a text file using I0 to send it to a text file or we can pipe our initial command so we can use multiple commands. 
* How to append the output of a command to a file
We can append the output of a command using a `>` for messages given during a successful process and `2>` for error messages. 
* How to use wildcards 
`*.txt` the star does not care and will find anything that matches the specified words. 
`b??h.*` the question mark represents only one unknown character and from ther will look for the other parameters set. 
`[0-9]` This will find anything that has a number. The [] will match any characters that is a member of the character set.
  * For copying a moving multiple files at the same time 
   When copying or moving multiple files at the same time we can use wildcards paired with wildcards to find files relative to our current use case.
* How to use brace expansion 
Brace expansion is used in some cases like this:
`mkdir -p ~/cis106f22/{labs{/kirby,/dreamland},COD}`
  * For creating entire directory structures in a single command

Same as the command provided above.

