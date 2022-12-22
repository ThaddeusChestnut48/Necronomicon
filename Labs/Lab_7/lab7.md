# Lab 7 - Handling Files
## Question 1: cat,tac,head,tail
1. Display the content of the `etc/passwd` file.
![q1.1.7](q1.1.7.png)
2. Display the content of the `etc/passwd` file in reverse order.
![q1.2.7](q1.2.7.png)
3. Display the content of the `etc/passwd` file with line numbers and the $ to indicate the end of every line. 
![q1.3.7](q1.3.7.png)
4. Display the first 5 lines of a the `etc/passwd` file. 
![q1.4.7](q1.4.7.png)
5. Display the last 5 ines of the `etc/passwd` file.
![q1.5.7](q1.5.7.png)

> Take a screenshot of **YOUR TERMINAL ONLY** showing all the commands that you used to complete this question

## Question 2: cut
1. Display the first field of the `etc/passwd` file.
![q2.1.7](q2.1.7.png)
2. Display the first and last field of the `etc/passwd` file
![q2.2.7](q2.2.7.png)
3. Display the first and last field of the `etc/passwd` file with the = as the output delimiter.
![q2.3.7](q2.3.7.png)
4. Display all the fields of the `etc/passwd` file except the 3rd field.
![q2.4.7](q2.4.7.png)

> Take a screenshot of **YOUR TERMINAL ONLY** showing all the commands that you used to complete this question
   
## Question 3: Paste, wc
1. Download these files using curl. Use the command: `curl -s URL-here -o name-of-file` where the name of the file is the one given in the URL. After Downloading the files, paste the files
* https://cis106.com/assets/shopping.txt
* https://cis106.com/assets/tasks.txt
![q3.1.7](q3.1.7.png)
2. How many lines does the book dracula book have? 
![q3.2.7](q3.2.7.png)
3. How many words does the book "Pride and Prejudice" have? 
![q3.3.7](q3.3.7.png)
4. Sort the file `/etc/passwd` 
![q3.4.7](q3.4.7.png)

> Take a screenshot of **YOUR TERMINAL ONLY** showing all the commands that you used to complete this question
   
## Question 4: tr, grep 
1. Replace the `;` for a `,` in the `cereal.csv` file 
![q4.1.7](q4.1.7.png)
2. Display every line that contain the word love in the book *"Pride and Prejudice"*
![q5.2.7](q4.2.7.png)
3. Display every line that contains exactly the word love or hate in the book *"Pride and Prejudice"* with line numbers
![q5.3.7](q4.3.7.png)
4. Display every line that starts exactly with the word **"love"** in the book Dracula. 
![q5.4.7](q4.4.7.png)
![q5.5.7](q4.5.7.png)
![q5.6.7](q4.6.7.png)
5. Display every line that starts with an upper case latter or a number in teh book Dracula.
![q5.7.7](q4.7.7.png)
![q5.8.7](q4.8.7.png)
![q4.9.7](q4.9.7.png)
![q5.1.7](q4.10.7.png)
![q5.1.7](q4.11.7.png)

> Take a screenshot of **YOUR TERMINAL ONLY** showing all the commands that you used to complete this question
    
## Question 5: 
1. Print the first and last field of the `cars.csv` file
![q5.1.7](q5.1.7.png)
2. Print the first and last field of the `cars.csv` file with the string `" made in "` as a delimiter
![q5.1.7](q5.2.7.png)
3. Print the `cars.csv` file in such a way that the output looks like this for every line:
   > The Chevy S-10 has 4 cylinders and is made in US
![q5.1.7](q5.3.7.png)
4. Print the `cars.csv` file excluding the first 2 records (lines).
![q5.1.7](q5.4.7.png)
5. Print all the car names in upper case. 
![q5.1.7](q5.5.7.png)
6. Replace all the instances of the word `Dracula` for the word `Alucard` in the book dracula. 
![q5.1.7](q5.6.7.png)
7. Insert a blank line after each line in the `/etc/passwd` file
![q5.1.7](q5.7.7.png)
8. Replave all the repeated blank lines for a single blank line in the book *"Pride and Prejudice"*
![q5.1.7](q5.8.7.png)

> Take a screenshot of **YOUR TERMINAL ONLY** showing all the commands that you used to complete this question

## Question 6 I/0 Redirection
1. How many users can login with the `/bin/bash` shell?
![q6.1.7](q6.1.7.png)
2. How many users have the `/sbin/nologin` shell assigned?
![q6.2.7](6.2.7.png)
3. How many ford vehicles are there in the `cars.csv` file
![q6.2.7](6.3.7.png)
4. How many 4 letter words are there in the bible?
![q6.2.7](q6.4.7.png)

> Take a screenshot of **YOUR TERMINAL ONLY** showing all the commands that you used to complete this question

## Challenge Question 
1. Display on the names of the cereals in the `cereal.csv` file *(Tip: use cut, awk and the pipe)*
![q7.1.7](7.1.7.png)
2. Sort the output of the previous command and sace it to a file called `cereal-sorted.csv` *Beware that the first 2 lines need to be removed)*
![q7.1.7](7.2.7.png)
3. Display the names of the cereals and the amount of calories they have per serving. 
![q7.1.7](7.3.7.png)
4. Repeat the previous command but replace the `;` with a `,`
![q7.1.7](7.4.7.png)

> Take a screenshot of **YOUR TERMINAL ONLY** showing all the commands that you used to complete this question