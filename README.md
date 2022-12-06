# 0x00. Python - Hello, World

Author’s disclaimer

    Welcome to the Python world!

    The first projects are more "C-oriented" - no tricks, no funky syntax - simple!
    If you've already played with Python, don't worry, fun things will come.
    You'll soon find that with Python (and the majority of higher level languages), there are ten different ways to do the same thing. Some tasks will expect only one implementation, while other tasks will have multiple possible implementations.
    Like C, Python also has a linter / style guide like Betty, called PEP8, also now known as PyCode.

    Enjoy!

    - Guillaume

![image](https://user-images.githubusercontent.com/111166573/204587568-13b13fed-d906-44d6-9948-11660079374a.png)


Pycodestyle

    Pycodestyle is now the new standard of Python style code (https://github.com/PyCQA/pycodestyle/issues/466)
        

# More Info
### Zen
        The Zen of Python, by Tim Peters

        Beautiful is better than ugly.
        Explicit is better than implicit.
        Simple is better than complex.
        Complex is better than complicated.
        Flat is better than nested.
        Sparse is better than dense.
        Readability counts.
        Special cases aren't special enough to break the rules.
        Although practicality beats purity.
        Errors should never pass silently.
        Unless explicitly silenced.
        In the face of ambiguity, refuse the temptation to guess.
        There should be one-- and preferably only one --obvious way to do it.
        Although that way may not be obvious at first unless you're Dutch.
        Now is better than never.
        Although never is often better than *right* now.
        If the implementation is hard to explain, it's a bad idea.
        If the implementation is easy to explain, it may be a good idea.
        Namespaces are one honking great idea -- let's do more of those!


## Concepts

    For this project, we expect you to look at this concept:

    + Python programming( https://alx-intranet.hbtn.io/concepts/550):
    
    + The Python Tutorial (https://alx-intranet.hbtn.io/rltoken/Fl7kjKxXgkbmX5P0-4k4tQ)
    + Python Programming: An Introduction to Computer Science 3rd edition (https://iran-lms.com/images/images/Books/PDF/Python-Programming_-An-Introduction-to-Computer-Science-Franklin-Beedle--Associates-2016---John-M.-Zelle.pdf)
    + Derek Banas’ Learn to program (https://alx-intranet.hbtn.io/rltoken/RNQj-DQDjG_lOzQn_ku2eg)
    + The Python Guru (https://alx-intranet.hbtn.io/rltoken/5U-qFDOGHyBSCLg2A37ILA)
    + New string formatting (https://alx-intranet.hbtn.io/rltoken/SUwBgkKMH7wiedG57WcT9A)
    + Garbage collector (https://alx-intranet.hbtn.io/rltoken/CimKF3MlfErabvZWtFxHjg)
    + Python Interpreter (https://alx-intranet.hbtn.io/rltoken/a5z3uSkiby1Xw679cFiw1Q)
    + Python bytecode (https://alx-intranet.hbtn.io/rltoken/oJ2v8bVCLZmAowJ7WXLzJg)


## Resources
### Read or watch:

    + [The Python tutorial (only the first three chapters below)](https://alx-intranet.hbtn.io/rltoken/JsFCs_NBzMAR7-XPAZ9BoA)
    + [Whetting Your Appetite](https://alx-intranet.hbtn.io/rltoken/kifRlLG2iMX5AZiW8lrCMg)
    + [Using the Python Interpreter](https://alx-intranet.hbtn.io/rltoken/RVpfAuagCo9SdfYeoHd6jg)
    + [An Informal Introduction to Python](https://alx-intranet.hbtn.io/rltoken/bVps0ZPWq7qVZ7vc-eJGTw)(Read up until “3.1.2. Strings” included) 
    + [How To Use String Formatters in Python 3](https://alx-intranet.hbtn.io/rltoken/Ju0J8BxkuPX5yKZctyKfsQ)
    + [Learn to Program](https://alx-intranet.hbtn.io/rltoken/szBsJ-Qyig_RrImN7RGlOg)
    + [Pycodestyle – Style Guide for Python Code](https://alx-intranet.hbtn.io/rltoken/tgYt-0zVy1T4sDlE9ohxnA)


## Learning Objectives
    At the end of this project, you are expected to be able to explain to anyone(https://alx-intranet.hbtn.io/rltoken/TYWTMEj3W1HhTHqMKu8kWA), without the help of Google:

### General
     + Why Python programming is awesome
     + Who created Python
     + Who is Guido van Rossum
     + Where does the name ‘Python’ come from
     + What is the Zen of Python
     + How to use the Python interpreter
     + How to print text and variables using print
     + How to use strings
     + What are indexing and slicing in Python
     + What is the official Python coding style and how to check your code with pycodestyle
  
## Copyright - Plagiarism
      + You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
      + You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
      + You are not allowed to publish any content of this project.
      + Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements
### Python Scripts
      + Allowed editors: vi, vim, emacs
      + All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
      + All your files should end with a new line
      + The first line of all your files should be exactly #!/usr/bin/python3
      + A README.md file at the root of the repo, containing a description of the repository
      + A README.md file, at the root of the folder of this project, is mandatory
      + Your code should use the pycodestyle (version 2.8.*)
      + All your files must be executable
      + The length of your files will be tested using wc

### Shell Scripts
      + Allowed editors: vi, vim, emacs
      + All your scripts will be tested on Ubuntu 20.04 LTS
      + All your scripts should be exactly two lines long (wc -l file should print 2)
      + All your files should end with a new line
      + The first line of all your files should be exactly #!/bin/bash
      + All your files must be executable

### C Scripts
      Allowed editors: vi, vim, emacs
      All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
      All your files should end with a new line
      Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
      You are not allowed to use global variables
      No more than 5 functions per file
      In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
      The prototypes of all your functions should be included in your header file called lists.h
      Don’t forget to push your header file
      All your header files should be include guarded


# 0x01. Python - if/else, loops, functions
![](https://alx-intranet.hbtn.io/images/challenge2022/get-started.jpg)

![](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/233/code.png)

## Resources
 Read or watch:

    + [More Control Flow Tools](https://alx-intranet.hbtn.io/rltoken/jpjs5EnZTpBLLEremJYjPQ) (Read until “4.6. Defining Functions” included)
    + [IndentationError](https://alx-intranet.hbtn.io/rltoken/F9n2AE-fpEPzt2PfBMGYAQ)
    + [How To Use String Formatters in Python 3](https://alx-intranet.hbtn.io/rltoken/ZdtRIAkFu8dMBT99DcFBNg)
    + [Learn to Program](https://alx-intranet.hbtn.io/rltoken/ElQgZYNHrLI7kV_ysEB1hQ)
    + [Learn to Program 2 : Looping](https://alx-intranet.hbtn.io/rltoken/ElQgZYNHrLI7kV_ysEB1hQ)
    + [Pycodestyle – Style Guide for Python Code](https://alx-intranet.hbtn.io/rltoken/TuTTnEg_Rwn8U1g3PEsZmA)

man or help:
    + python3

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
    + Why Python programming is awesome
    + Why indentation is so important in Python
    + How to use the if, if ... else statements
    + How to use comments
    + How to affect values to variables
    + How to use the while and for loops
    + How is Python’s for different from C‘s?
    + How to use the break and continues statements
    + How to use else clauses on loops
    + What does the pass statement do, and when to use it
    + How to use range
    + What is a function and how do you use functions
    + What does return a function that does not use any return statement
    + Scope of variables
    + What’s a traceback
    + What are the arithmetic operators and how to use them

## Copyright - Plagiarism
    + You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
    + You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
    + You are not allowed to publish any content of this project.
    + Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements
### Python Scripts
    + Allowed editors: vi, vim, emacs
    + All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
    + All your files should end with a new line
    + The first line of all your files should be exactly #!/usr/bin/python3
    + A README.md file, at the root of the folder of the project, is mandatory
    + Your code should use the pycodestyle (version 2.8.*)
    + All your files must be executable
    + The length of your files will be tested using wc

### C Scripts
    + Allowed editors: vi, vim, emacs
    + All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
    + All your files should end with a new line
    + Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
    + You are not allowed to use global variables
    + No more than 5 functions per file
    + In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
    + The prototypes of all your functions should be included in your header file called lists.h
    + Don’t forget to push your header file
    + All your header files should be include guarded

### More Info
Note: you do not need to understand lists yet.

