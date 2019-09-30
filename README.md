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

Complete the Exam 1 activities using bash code. It is assumed that your will be in your Exam 1 repo directory and that files will not be moved unless specified. 

1. Clone your repository for this exam to your local computer. 
	* If you have a Win10 computer, then I want you to clone your Exam 1 repo into the windows `Documents` directory. Here is pseudocode to help you get there in your terminal.
	```bash
	cd /mnt/c/Users/YOUR_WINDOWS_USERNAME/Documents
	```
	
	* If you have a MAC computer, then I want you to clone your Exam 1 repo into your home dir.
	```bash
	cd ~
	```
	

2. Create a file called `exam1_solutions.sh` in `notepad++` or `bbedit` to record your answers in the form of a script.  Save it to your Exam 1 repo dir.

3. Take a snapshot of the changes to your Exam 1 repo dir using git.

4. On line 1 of `exam1_solutions.sh`, add a `bash` shebang!.  

5. In the Buzzard et al 2015 data set, use bash commands to determine which species is the most widespread, and thus occurs in the most plots.
	Code should return output as follows:
	```bash
	$ code to isolate the species observed in the most plots
	Genus species
	```
	
	* On line 3 of `exam1_solutions.sh`, copy and paste this question (5. In the Buzzard ... most plots.) and make it a comment
	* On line 4 of `exam1_solutions.sh`, copy and paste your working line of code (do not indent).
	* Save the changes you made to `exam1_solutions.sh` then take a snapshot of your Exam 1 repo dir with git.

6. Take your line of code from question 5 and save it into a variable named `MostWidespreadSpecies`

	* On line 6 of `exam1_solutions.sh`, copy and paste this question and make it a comment
	* On line 7 of `exam1_solutions.sh`, copy and paste your working line of code (do not indent).

7. Write a line of code that that uses the variable you made in question 6 to print the following to the screen:
	```bash
	The most widespread species is *Genus species*
	```
	* On line 9 of `exam1_solutions.sh`, copy and paste this question and make it a comment
	* On line 10 of `exam1_solutions.sh`, copy and paste your working line of code (do not indent).
	* Save the changes you made to `exam1_solutions.sh` then take a snapshot of your Exam 1 repo dir with git.

8. Write a line of code that that sets a new variable called `MostWidespreadSpeciesComma` with the contents formatted as follows: `Genus,species` then use this new variable to make a file named `Abund.n_Genus_species.dat` with the abundance of the most widespread species in each plot:
	```bash
	$ MostWidespreadSpeciesComma=insert code here
	$ insert code here to create the file called Abund.n_Genus_species.dat
	```
	* On line 12 of `exam1_solutions.sh`, copy and paste this question and make it a comment
	* On line(s) 13-14 of `exam1_solutions.sh`, copy and paste your working line(s) of code (do not indent).
	* Save the changes you made to `exam1_solutions.sh` then take a snapshot of your Exam 1 repo dir with git.

9. Use a for loop to add up the total number of trees recored in `Abund.n_Genus_species.dat` and then print the result to the screen as outlined below: 
	```bash
	$ for variableA in $(code to list contents of Abund.n_Genus_species.dat); do
	  variableB=$variableB + $variableA 
	  done
	$ code to print result to screen
	There were variableB Genus species recorded by Buzzard et al (2015).
	```
	* On line 16 of `exam1_solutions.sh`, copy and paste this question and make it a comment
	* On line(s) 17-20 of `exam1_solutions.sh`, copy and paste your working line(s) of code (do not indent).
	* Save the changes you made to `exam1_solutions.sh` then take a snapshot of your Exam 1 repo dir with git.

* Use git to submit your assignment by pushing it back to your Exam 1 repo on GitHub.
