# **Programming and Scripting Module 2019 - Problem Set Solutions**

## **Name: Niamh O'Leary**

## **Student ID: G00376339**


## **Problem set solutions**

This respository contains my solutions to the Problem Set 2019 for the module Programming and Scripting at GMIT.

### **How download this respoitory**
1. Go to Github and select pands-problem-set. 
2. Click the download button.

### **How to run the code**
1. Make sure you have Python installed. https://www.python.org/downloads/
2. Download Python using Anaconda and use iPython. https://www.anaconda.com/distribution/
3. Anaconda allows you to use software such as Visual Studio Code. https://code.visualstudio.com/download
4. Download Vivual Studio Code, this will assist you in saving annd editing your code.
5. Install Cmder in Windows to allow you run the code used in this repository. https://cmder.net/
6. Open a command winder and use ipython. 


### **Introduction**

I am total novice to python and programming in general. Therefore, before I attempted the Problem Set, I did a number of online practical tutorials. I repeated the exercises in these tutorials until I was more confident with some of the coding and syntaxes used in python. 

References:
www.w3schools.com/python
www.udemy.com
  "Complete Python Bootcamp: Go from zero to hero in Python 3"
  "Learning Python for Data Analysis and Visualisation"
  
  
### **Exercise 1**
Filename: solution-1.py contains my solution to problem one.
Write a programme that asks the user to input any positive integer and outputs the sum os all numbers between one and that number?

Solution: This program for sum of digits in python allows the user to enter any positive integer and then, that number is assigned to variable Number. Next, Condition in the While loop will make sure that, the given number is greater than 0 (Means Positive integer and greater than 0)

References:
McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.
https://www.w3resource.com/python/python-tutorial.php
https://www.tutorialgateway.org/python-program-to-find-sum-of-digits-of-a-number/


### **Exercise 2**

Filename: solution-2.py contains my solution to problem two.

Write a program that outputs whether or not today is a day that begins with the letter T. 
To solve this problem I had to get the current date by using the datetime script to give me the current date and time. I assigned the days of the week which begin with the letter T a number. By using an IF statement, I was able to check if the day of the week selected started with T, if so the script acknowledged this an being true otherwise the script returned false. 

McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.


### **Exercise 3**
Filename: solution-3.py contains by solutions to problem 3.


Write a program that prints all numbers between 1,000 and 10,000 that are devisible by 6 but not 12. 

Solution: To solve this problem, I used "for" and "range ()", which allowed me return a sequence of numbers and allowed my program to iterate over a sequence. Which is also called a traversal. By putting range (1000, 10000), I was able to identify the range of numbers I wanted in my sequence from 1000 to 10000. I assigned the identify of "num" to this. I then used an "if" statement to identify all the numbers which were divisible by 6 by using the equals code " a==b". I also a second part to my "if" to allow me identify all the numbers divided by 12, I used the not equals condition "a !=b".

Reference:
McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.
www.pythoncentral.io/pythons-range-function-explained/
www.w3schools.com/python/ref_func_range.asp



### **Exercise 4**
Filename: solution-4.py contains my solutions to problem 4.

Write a program that asks the user to input any positive integer and outputs the sucessive values of the following calculation. At each step calculate the next value by taking the current value and, if it is even, divide by two, but if it is odd, multiply it by three and add one. Have the programe end if the current value is one.

Solution: To solve this problem I used the COLLATZ CONJECTURE function, which is a conjecture that a particular sequence always reaches 1. The sequence is defined as start with a number n. I combined an ELSE statement with an IF statement. An ELSE statement contained the block of code that executes if the conditional expression in the IF statement resolves to 0 or a FALSE value. I also used the ELIF statement which allowed me check multiple expressions for TRUE and execute a block of code as soom as one of the conditions was TRUE. I initially was unsure as how to tackle this problem. However, I looked at other exmmples in GITHUB and StackOverFlow for guidance and then researched using the IF, ELSE and ELIF statements. 

Refernces:
McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.
www.stackoverflow.com/questions/33505034/making-a-collatz-program-automate-the-borning-stuff



### **Exercise 5**
Fiename: solution-5.py contains solution to problem 5.

Write a program that askes the user to input a positive integer and tells the user whether or not the number is a prime.

Solution: Before I could start this exercise, I had to research prime numbers. A prime number is a number whose only factors are 1 anf itself. Examples of prime numbers are 2, 3, 5, 7, 13, 17. Greek mathematician Euclid was the first to provide proof that there are unfinately many primes. Therefore N = p1...pn + 1. The largest know prime number has more that 23 million digits and is referred to as M7723917.

To run a program for this exercise, I had to understand the following topics in Python, if...else statement, Loop, break and contontinue. An "if...else" statement is used to make a decision. A "loop" statement iterates over a sequence. Finally, by using "break and continue", I was able alter the flow of the loop. In this program I have checked if the number inputted by the user is checked if it is a prime number or not. If the number can be divided by any number from 2 to -1, the number is not a prime. Otherwise the number is a prime number. 

Refernces: 
McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.
https://whatis.techtarget.com/defination/prime-number
wwww.programiz.com/python-programming/examples/prime-number


### **Exercise 6**
Filename: solution-6.py conatians solution to problem 6.

Write a program that takes a user input string and outputs every second word.

Solution: To solve this exercise, I had to research how to split a string in Python. By using split() I was able to split the string into a list. I then searched how to select every second word and discovered that I could use the notation [::2] which is based on the concept of "slicing". The string "the quick brown fox jumps over the lazy dog

Refernces:
www.pythonforbeginners.com/dictionary/python-split
www.w3schools.com/python/ref_string_split_asp
McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.
https://stackoverflow.com/questions/17645327/python-3-3-how-to-grab-every-5th-word-in-a-text-file

### **Exercise 7**
Filename: solution-7.py contains my solutions to problem 7.

Solution: I was able to find the square root by using the SQUARE ROOT FORMULA. I researched the formula by undertaking a search in StackOverFlow and Programiz web tutorial. 

Refernces: 
McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.
https//www.programiz.com/python-programming/examples/square-root

### **Exercise 8**
Filename: solution-8py containes my solution to problem 8.

Solution: To solve this problem, I revisted the datetime moddule that I used in problem 2. I was albe to generate today's date, but was unsure as how to display it in the requested format. I researched datetime modules in The Python Tutorial and found a way to manipulate the datetime by using strftime () method, this allowed me take format codes and return a formatted string based on these codes. By using the now vairable, I was able to select the current datte and time. I then used strftimes directives to give the date and time in the required foramt.
      Code                  Meaning                           Example
      %A                    Full weekday name                 Sunday
      %B                    Full month name                   March
      %d                    day of the month                  17 by adding th I got 17th
      %Y                    year in four digit format         2019
      %I                    hour using 12 hour clock          10
      %M                    minute                            31
      %p                    either am or pm                   pm


Refernces:  
www.w3resource.com/python-exercises/python-basic-exercise-3.php
httpS//docs.python.org/3/library/datetime.html.
www.strftime.org
McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.

### **Exercise 9**
Filename: solution-9.py contains solution to problem 9. 

Solution: In solving this problem I firstly search for and saved Chapter 1 Mody Dick as a text file. I then researched how to open a text file in python.  By using open ('moby-dick', 'r') I was able to open the file for reading plan text. I then wrote code so that every line in the file would be read. By using the built in function enumerate () I was able to loop over the text and create a tuple. I then identified that I only needed every second line to be selected. 

Refernces: 
McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.
The Python Tutorial 3.7, secion 7.2 - Reading and Writing Files.


### **Exercise 10**
Filename: solution-10.py contains solution to problem 10. Each plot is saved as a .png file.
Filename: solution-10-b.py contains the solution to problem 10. The three plots are displayed on one graph. This was my second and revised attempt at this question.

Solution: To solve this problem, I had to use matplotlib and numpy. To gain a better understaning of the general concepts of matplotlib, I worked my way throught eh introductory tutorial at Matplotlib Version 3.0.3. I also referred to the NumPy manual available on SciPy.org, this gave me a greater understanding of the different function available in Numpy especially the np.arange function, which I used in my solution to return an array of evenly spaced numbers as per the interval I asked e.g 0.5. 

I initially approached this problem, by manually calculating the values of for the funtions I wanted to plot. I then created individual plots for each funtion. However, I researched a more effecient way to generate these plots on on graph. 

References:
www.matplotlib.org/tutorials/introductory/usage.html#sphx-glr-tutorials-introductory-usage.py
www.scipy.org/doc/numpy/index.html
VanderPlas, J. (2016), *A Whirlwind Tour of Python*, O'Reilly Media. 
https://www.tutorialspoint.com/matlab/matlab_plotting.htm
McLoughlin, I. (2019), *Lecture Presentations - 52445 - Programming and Scripting*, Higher Diploma in Computing and Data Analytics, Galway Mayo Institute of Technology.

## **Deployment**
Python 3.7.2 is the latest version available for download. For more information please go to https://www.python.org/

## **Built With**
- Python - https://www.python.org/downloads/
- cmdr - https://cmder.net/
- Visual Studio Code - https://code.visualstudio.com/download
- Anaconda - https://www.anaconda.com/distribution/

## **Authors**
- Niamh O'Leary - initial work as part of Problem Set for H.Dip in Computing and Data Analytics, GMIT.

## **Acknowledgements**
- Dr. Ian McLoughlin, Dept. of Computer Science, GMIT. 
