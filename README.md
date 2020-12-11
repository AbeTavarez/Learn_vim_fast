# Learn_vim_fast

# Basics ✏️

Hello, 👋🏻 welcome to a fast intro to that VIM Editor...

First things first, what's VIM?

VIM is a text editor that works inside your terminal. You'll find it in almost all Unix/Linux/Mac systems.

Why would you want to learn how to use VIM?

Well, VIM is often used by developers, sysadmins, database admins and many more... Since they're often working from the "shell" or "terminal" is really easy to edit  a configuration file. Also many of those server programs don't even have a graphical user interface ("GUI") making being able to work with VIM a viral skill to have. 
 
There are others text editors you can use in the terminal (like nano), but they might not be universal for all systems. (As opposed to VIM that is always there for you!)

You should also know there is an older version of vim called "vi". We'll learn how to use vim which means "vi improved" since it's the defacto between the two.

## Let's geek out 🤓

Open your favorite terminal and type `vim`. You should see the following:

![vim editor](https://res.cloudinary.com/abetavarez/image/upload/v1607654746/Screen_Shot_2020-12-09_at_11.28.38_PM_yfegcw.png)

Great, now type `:q` and press enter. Amazing! You just learned how to open and quit vim.

Learning how to quickly open and quit seems like no big deal,  but vim has been known to be tricky to many beginners (myself included). This is due to the fact that vim has many ways to quit or exit the program.
  
But don't worry, I'll show you more useful ways to quit your program in the next task.

## Let's continue 👍

Now, let's create a new file in the same directory we are in.

Enter `vim testfile.txt` to create a file named 'testfile' and open it with vim.

![vim editor with empty file](https://res.cloudinary.com/abetavarez/image/upload/v1607655078/Screen_Shot_2020-12-10_at_9.50.16_PM_x7erix.png)

Now comes yet another tricky part. As soon as vim opens, it opens on "command mode" which make every key on your keyboard a command. 
Let's use one of those commands, press `i` on your keyboard.
You just told vim to go into "INSERT MODE". Now you can type anything you'd like:

![vim editor on insert mode]
(https://res.cloudinary.com/abetavarez/image/upload/v1607655497/Screen_Shot_2020-12-10_at_9.58.07_PM_ecj3wa.png)


When you're done typing, press the "escape" key on your keyboard to exit "INSERT MODE" , then type `:w` and press enter to "write" or "save" the file. Finally, type `:q` and press enter to exist vim. 

Another way to write and quit vim in a single command is `:wq` .  

To check that your file has been saved, type `cat testfile.txt`. This command will print the file content on your terminal. 

![file content printed to terminal]
(https://res.cloudinary.com/abetavarez/image/upload/v1607655930/Screen_Shot_2020-12-10_at_10.05.21_PM_gsrscm.png)

Voila! You just learned how to create and write a text file without leaving the comfort of your terminal.

## Editing

Let's say we need to edit this or any existing file.

Type `vim testfile.txt` Now you can move inside this file using the arrow keys or these: 

| Key        | Action           
| ------------- |:-------------
| l (lower case)| to move right 
| h (lower case)| to move left    
| j (lower case)| to move down
| k (lower case)| to move up

You can use the `l, h, j and k` to move around faster without having to move your hand from it's position. 
 


