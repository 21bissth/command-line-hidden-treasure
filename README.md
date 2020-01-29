# Command Line Hidden Treasure

#### <a id = "motivation"></a> Why learn command line?
Using the command line is a way for you to directly communicate with your computer. Rather than using something like Files, Finder or Windows Explorer, you can talk directly to your machine. Think about it like learning a new language, one that your computer is fluent in.

One way we can use the command line is to navigate through our files. In order to do this we need to be able to tell our computer **where** we want to go, and find out **what** is inside of the folder we're in.

#### Important first step
The only way to learn this is by doing. This means turning off the "graphical" view of your files, so you are forced to use the command line. Learning by doing.

To turn off the graphical view, find the little gear icon near the left-top part of your screen and turn off "show environment root".

It looks like this:

<img src="https://i.imgur.com/GUDVmVN.gif" width=300>

#### Other names for 'command line'

"command line" == "terminal" == "console"

Below we'll start to call it "terminal".

#### <a id = "find"></a> Where is my terminal?
You'll be using what you learn here in your terminal. This is a place where you can speak directly to your computer. In the cs50 ide, find the window that has `~/ $` and type `pwd`. You should see something like this:

<img src="https://i.imgur.com/fZLU7wJ.gif" width="200">

That's your terminal.

#### What files do you already have on your virtual machine?
Every time you see the `$`, that's your terminal waiting for you to tell it what to do.

First let's see what files you already have on your cs50 virtual machine. To do this, we'll ask the terminal to **l**i**s**t what's there. Type `ls` (short for "list") at the new `$` that appeared.

But hey, it doesn't list anything for you. Just a new `$` prompt. That's because your virtual machine is brand new! You don't have any directories (aka folders) or files on it yet.

#### How do I get some files?
We'll use a service called `git` to get (no relation) your first set of directories and files. Copy/paste the following after the new `~/ $` that appeared in your terminal, then hit enter:

`git clone https://github.com/woodstockcs/command-line-hidden-treasure.git`

You should see something like this:

<img src="https://i.imgur.com/8rEnlA0.gif" height="200">

Congratulations! Now you have some directories and files on your machine.

When you see a new prompt (`$`), type the command for list again (do you remember it? you used it above). Now you should see one directory listed.

#### <a id = "move"></a> How do I move into a directory?
Movement, an essential part of navigation! But how to accomplish it? Thankfully, we have the `cd` command, which stands for **c**hange **d**irectory. A directory is just another word for a folder, so we use this command to change our current folder.

To move in to a directory from where we currently are, we type `cd directory_name` then hit enter. But instead of "directory_name" we type the actual name of the directory we want to move into (the same name we saw displayed after `ls`).

Type the command to move into your new directory now.

Type `ls` to see the listing of what's in there.

Type `cd ..` to move out of that directory (or in programmer-speak: "up the directory tree").

Type `ls` again.

#### How do I read a file?

Type `open WarAndPeace.txt` to read a file called WarAndPeace.txt. Of course you can change that filename to whatever you want, as long as its a filename you can see when you `ls`.

***

# <a id = "lab"></a> Hidden Treasure Activity

Now that we've got the basics down, let's look around. The directories and files you got above (with `git`) contain a map of computer land, a magical place full of treasure.

#### Getting Started
Before you get started, make sure you're in the correct folder. If you run the command `pwd` in your terminal, the output should end in "command-line-hidden-treasure". If it doesn't, you'll need to "cd into that directory" (that's programmer speak) by typing `cd command-line-hidden-treasure`

#### Task
You'll be moving through the folders in this repository using the command line and looking for files called "X.txt". As we all know, X marks the spot. Be sure to use the `ls` command to see what is inside each folder you enter. Inside each file "X.txt" will be a new command that you can use in the command line, so look carefully! Every file will have a .txt extension, so anything that doesn't end in .txt is a folder and a potential treasure filled location.

Each time an `X.txt` file teaches you about a new command, try it out and **write it down** (because you'll use it later).

There are 5 X's total, so ready, set, and happy treasure hunting....

<img src="https://media.giphy.com/media/g6ZTtxTm7pYsw/giphy.gif" width=300>

***

#### Final steps
1. `cd` to your root directory. (The "root directory" is the one that looks like this `~/ $`.) You can get there with `cd ~`.
1. Create a new file called `cheatsheet.txt`
1. In that file, type out examples of each of the terminal commands (or tricks) you know so far and describe what each one does. Include what's above on this page: `cd` `ls` `open` `pwd` `git`, and also include the things you learn in the `X.txt` files. Be clear because you'll refer back to this when you forget one of these.
1. Save the file.
1. Take a screenshot of this file and copy it into your assignment questions doc in google classroom.

**Definition of done: You've followed all the steps above and pressed 'Turn in' for the assignment questions on google classroom.**

