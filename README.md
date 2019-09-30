# Exam 1

## Due 10/04

## Computer Preparation
* Win10
  * Log into your Ubuntu terminal.  _We will not use `gitbash` unless you can't get Ubuntu running._ You are in your home directory.

  * If the Ubuntu app is not installed or you are using an Ubuntu terminal that hasn't been setup (you'll know because it will ask you to create a new user name and password), then follow the instructions [here](https://github.com/cbirdlab/wlsUBUNTU_settings/blob/master/README.md) to set it up. Note that I have automated the process and you should be able to complete it in less than a minute.
  
  * If the `CSB` directory does not exist in your home directory (check with `ls`), then run the following code to clone the `CSB` repository into your home directory:
    ```bash
    git clone https://github.com/CSB-book/CSB.git
    ```

* MacOS

  * Open a terminal window

  * Consider installing [homebrew](https://brew.sh/).  You will be able to use homebrew to install linux software, such as `tree`, which is used in the slide show.
  
  * If the `CSB` directory does not exist in your home directory (check with `ls`), then run the following code to clone the `CSB` repository into your home directory:
    ```bash
    git clone https://github.com/CSB-book/CSB.git
    ```

## GitHub Preparation
* You must be a member of our class's github repository. If you are not a member (because you did not accept the initial invite) then please let me know and I'll reinvite you. 
* Make sure you are logged into github.

## Description of Exam 1 
* Clone the repository for this exam to your home dir in your terminal. 
* Complete the Exam 1 activities using bash code. It is assumed that your are in your Exam 1 repo directory and that files will not be moved unless specified. 

0. Create a file called `exam1_solutions.sh` in `notepad++` or `bbedit` to record your answers in the form of a script.  For now, you can save the file whereever you want.

1. On line 1 of `exam1_solutions.sh`, add a `bash` shebang!.

2. In the Buzzard et al 2015 data set, use bash commands to determine which genus is the most widespread, and thus occurs in the most plots.
	Code should return output as follows:
	```bash
	$ code to isolate the genus observed in the most plots
	Genus
	```
	
	* On line 3 of `exam1_solutions.sh`, copy and paste this question (2. In the Buzzard ...) and make it a comment
	
	* On line 4 of `exam1_solutions.sh`, copy and paste your working line of code (do not indent).
	
* Use git to track the changes made to your local Exam 1 repository as you complete the exercises
* Use git to submit your assignment by pushing it back to your Exam 1 repo on GitHub.
