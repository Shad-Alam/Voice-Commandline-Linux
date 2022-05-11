Project    : Voice Command Line in Linux Operating System

Language   : Python

Contributor: Shad-Alam

Description:

- This is a simple voice command line project for Linux Operating System. In this project, I execute linux command by using voice. 

Process:
1. First need voice.Voice convert into text.
2. Text can execute original command.

Implementation process:
1. Pocketsphinx is for Speech Recognition. It can convert speech to text.

   Pocketsphinx installation process:
   	-sudo apt-get update
	
	-sudo apt-get install pocketsphinx
	
	-sudo apt-get install -qq python3-dev python3-pip build-essential swig git libpulse-dev libasound2-dev
   
   Offical Installation link: https://githubhot.com/repo/bambocher/pocketsphinx-python 
2. If text is match, it will execute original command by using system function.

Project video presentation: https://youtu.be/-xsSXRHfxRE

* Released: May 10, 2022
