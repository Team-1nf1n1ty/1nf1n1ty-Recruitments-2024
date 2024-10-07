# 1nf1n1ty Recruitment 2024

Do you have what it takes to be a hacker? It is time to prove yourself! We believe that you can do this!
This document will guide you through the tasks you need to complete.

## Task 1 - OverTheWire Bandit Wargames

OverTheWire's Bandit Wargames is an online platform designed to help beginners develop and enhance their skills in Linux command-line and cybersecurity.
Website URL : `https://overthewire.org/wargames/bandit/`

For this task you have to complete all the 34 levels in the Bandit section on the "OverTheWire" website.
For this section, the major skill which you will require is using the "SSH" tool on command line.
SSH is needed to access the remote OverTheWire server, where all the Bandit challenges are hosted.
Each level in the game is on a remote machine, and you need a way to interact with it, for which SSH provides a secure connection.

General SSH Command Format : `ssh <username>@<host> -p <port>`

Here's how to do Level 0 for an example :

Description : The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

Command : `ssh bandit0@bandit.labs.overthewire.org -p 2220`

Password : bandit0

Now beginning from Level 1, it's your turn to show us what you've got!

Each level demands from you, the knowledge of various Linux commands like cat, du, ls, find, etc.
Every level consists of attached documents which will help you with the skill required in that particular level.
Your goal in each level is to get the password in order to unlock the next level.

What you need to do :

1. Solve all the 34 levels in the Bandit section of OverTheWire.
2. Prepare a write-up, documenting the commands you used in each level.
3. Create a **private** GitHub repository called "1nf1n1ty-recruitment". You will place the writeups of all the tasks in this repo.
4. Create a folder called "Bandit-Games" inside this repo, where you will store the writeups for all levels

## Task 2 - PWN College Modules

PWN College is a free educational platform for learning and practicing Cybersecurity concepts. We are going to focus on their "Intro to Cybersecurity" section.
Website URL : `https://pwn.college/intro-to-cybersecurity/`

For this task you have to do first three modules:

1. Talking-Web (upto level18)
2. Building a Web Server
3. Web Security (upto SQLi5)

Note: If you do more or finish the modules it will be considered as bonus ;)

As you do these modules, prepare a write-up along side noting which commands you used to solve the level and why it worked. Once you finish this, Create a folder called "PWN-College" in the repo you created earlier and push the write-up into that folder.

## Task 3 - Data Encoder and Decoder using Python

**WARNING : Please do not use ChatGPT or any other Generative AI tools to solve this task. You may refer python documentation, StackOverflow or other tutorial websites only.**

Python is a very essential part of CTFs, hence it is important to have a good proficiency in python. Also, when you are playing CTFs, you will find yourself encountering data encoded in various formats. Most beginners use dedicated websites to decode the data. But wouldn't it be more convenient to have a tool at your disposal that will do it for you ?

Your third task is to build a Data encoder and decoder using python. You may use built-in methods. You will have to consider the following encoding schemes.

1. Base64
2. Hexadecimal
3. Binary
4. Octal

Your python code should be able to encode a plaintext into one of these formats, as well as decode an encoded text. You will be giving 3 inputs, one to specify whether to perform encoding or decoding, one to pick the encoding scheme and one to give the plaintext/encoded text.

A sample output is shown below

```bash
cmd> python task3.py
Enter 1 for encode or 2 for decode : 2
Menu
1) Base64
2) Hexadecimal
3) Binary
4) Octal
Enter the encoding scheme : 2
Enter encoded text : MW5mMW4xdHk=
Decoded Text : 1nf1n1ty
```

Bonus points if you are able to take the inputs using command line arguments !!

Once you are done, create a folder called "Python" in the repo you created earlier, and push your code into that folder. Also add output screenshots in the same folder.
**Please note that sharing your solutions with other participants is strictly prohibited and may lead to your disqualification from the recruitment process**

That is all about the 3 tasks you need to finish! Once you complete and document them, you will need to give us collaborator access. To do that, follow the steps outlined below.

1. Go to repo settings
2. Click on Collaborators in the sidebar
3. Login to your GitHub Account if prompted
4. Click on Add People
5. Type in [team1nf1n1ty](https://github.com/team1nf1n1ty) and then click on Add to Repository.

That's it! Once you have completed the above steps, notify us on WhatsApp so that we can have a look at your writeups. We hope that you enjoy these tasks, and we are looking forward to see you in the team soon :)
