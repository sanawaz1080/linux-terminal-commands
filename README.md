# Linux & Terminal Commands

### What is Linux?

Linux is an operating system's kernel. You might have heard of UNIX. Well, Linux is a UNIX clone. But it was actually created by Linus Torvalds from Scratch. Linux is free and open-source, that means that you can simply change anything in Linux and redistribute it in your own name! There are several Linux Distributions.

- Ubuntu Linux
- Red Hat Enterprise Linux
- Linux Mint
- Debian
- Fedora

Linux is Mainly used in servers. About 90% of the internet is powered by Linux servers. This is because Linux is fast, secure, and free! The main problem of using Windows servers are their cost. This is solved by using Linux servers. The OS that runs in about 80% of the smartphones in the world, Android, is also made from the Linux kernel. Most of the viruses in the world run on Windows, but not on Linux!

### What Is a Linux Command?

A Linux command is a program or utility that runs on the CLI – a console that interacts with the system via texts and processes. It’s similar to the Command Prompt application in Windows.

Linux commands are executed on Terminal by pressing Enter at the end of the line. You can run commands to perform various tasks, from package installation to user management and file manipulation.

Here’s what a Linux command’s general syntax looks like:

**CommandName [option(s)] [parameter(s)]**

A command may contain an option or a parameter. In some cases, it can still run without them. These are the three most common parts of a command:

- **CommandName** is the rule that you want to perform.
- **Option** or **flag** modifies a command’s operation. To invoke it, use hyphens (–) or double hyphens (—).
- **Parameter** or **argument** specifies any necessary information for the command.

**Keep in mind that all Linux commands are case-sensitive.**

### 1. ls

In the current folder, if you want to list the all the items you can use **ls command**

`ls`

To see other directories content, type ls followed by the desired path. For example, to view files in the Documents folder, enter:

`ls /home/username/Documents`

Here are some options you can use with the ls command:

- `ls -R` lists all the files in the subdirectories.
- `ls -a` shows hidden files in addition to the visible ones.
- `ls -lh` shows the file sizes in easily readable formats, such as MB, GB, and TB.

### 2. mkdir

**mkdir command** is used to create a directory

`mkdir dirname`

### 3. cd

To navigate through the directories, use the **cd command.**

`cd dirname`

Here are some shortcuts to help you navigate:

- `cd ~[username]` goes to another user’s home directory.
- `cd ..` moves one directory up (move back).

### 4. pwd

Use the pwd command to find the path of your current working directory. Simply entering pwd will return the full current path.

`pwd`
