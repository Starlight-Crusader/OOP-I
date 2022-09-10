# OOP-I (FAF-211 - Kalamaghin Arteom)
This file will act as a report on the work done. In the folders You can find
all the materials: sreenshots and scripts.

## Task I
I have intalled a UNIX-based operating system - Linux (Ubuntu) as dual boot.

## Task II 
In order to install zsh I've executed the following commands in the Terminal:
	1. sudo apt-get update;
	2. sudo apt-get intall zsh -y;
	3. chsh -s /usr/bin/zsh (makes the zsh to be the default shell);
	4. zsh (configuration process).

Then I've installed and configured (picked a theme) oh-my-zsh:
	1. sudo apt install curl git;
	2. sh -c "$(curl -fsSL *URL)";
	3. nano ~/.zshrc
(In the screenshots folder You can see I've picked af-magic.zsh-theme).

## Task III
I've installed the gcc compiler as part of the build-essential package and
checked the version I've istalled:
	1. sudo apt-get install;
	2. gcc --version ("gcc (Ubuntu 11.2.0-19ubuntu1) 11.2.0").

Then I had wrote "hello.c" and compiled it executing: "gcc hello.c -o hello".
After that I've prepared "makefile" that after *make hellomake* compiles
the listed scripts (hello.c) into an executable - "hello"
(execute with ./hello).

## Work with git
First of all I've created a remote gitHub repository in web-browser and
cloned it with "git clone" into a local folder. I've stored all the materials
in this folder, commited and pushed them ("git status", "git add .",
"git commit -m", "git push").
