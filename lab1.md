# Remote Access and FileSystem (Week 1)

*Welcome to CSE 15L! This tutorial will help you log into a course-specific account on ieng6*


### Installing VScode

* Visit the [Visual Studio Code Website](https://code.visualstudio.com/) and follow the download instructions for your operating system
* After following the download instructions, VScode should look like this:

![Image](VSCodeScreenshot.png)


### Remotely Connecting
*This step involves using VScode/terminal to connect and work on a remote computer over the internet*

* To install Git, windows users must access this [link](https://gitforwindows.org/) and follow download instructions
* Upon installation, you will need to set git bash as your default terminal. Instructions for this can be found [here](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994)
* If the steps were followed correctly, your terminal (CTRL + SHIFT + ') should look like this :

![Image](TerminalPreview.png)

* In order to use ssh, you will have to type the following command in the terminal:

`$ ssh cs15lsp23XX@ieng.ucsd.edu` (XX will be replaced by the corresponding letters from your account)

* After you run this command, you will be asked to answer an authenticity question, to which you should respond yes.
* Now you will be prompted to enter the password for your account. (Note : When you start typing, there will be no changes on the screen, but type your entire password and press enter to continue)
* If connected successfully, your terminal should look like this:

```
Hello cs15lsp23XX, you are currently logged into ieng6-202.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   14:45:01   9  1.00,  1.13,  1.11
ieng6-202   14:45:01   5  4.01,  4.29,  4.24
ieng6-203   14:45:01   7  1.28,  1.32,  1.23


Sun Apr 09, 2023  2:45pm - Prepping cs15lsp23

```



