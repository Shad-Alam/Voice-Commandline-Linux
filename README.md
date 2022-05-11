Project    : Voice Command Line in Linux Operating System

Language   : Python

Contributor: Shad-Alam

Description:

- This is a simple voice command line project for Linux Operating System. In this project, I execute linux command by using voice. I tested this project on ubuntu 20.04.

Process:
1. First need voice.Voice convert into text.
2. Text can execute original command.

Implementation process:
1. Pocketsphinx is for Speech Recognition. It can convert speech to text.

   Pocketsphinx installation process:
   	
	-sudo apt-get update
	
	-sudo apt-get install pocketsphinx
	
	-sudo apt-get install -qq python-dev python-pip build-essential swig git libpulse-dev libasound2-dev
   
   Offical Installation link: https://githubhot.com/repo/bambocher/pocketsphinx-python 
2. If text is match, it will execute original command by using system function.

How to run this project?

First install,

- sudo apt install geany

- sudo apt install scrcpy

Now,

1. open terminal and run
  - git clone https://github.com/Shad-Alam/Voice-Commandline-Linux.git
  
2. cd Voice-Commandline-Linux

3. python3 joy.py

Project video presentation: https://youtu.be/-xsSXRHfxRE

* Released: May 10, 2022
