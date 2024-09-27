# Exam 1

---

## Description of Exam 1 

### I. Knowledge Gained and Comprehension (worth 50% of total exam grade)
[Answer the questions linked here.](https://forms.office.com/Pages/ResponsePage.aspx?id=8frLNKZngUepylFOslULZlFZdbyVx8RLiPt1GobhHnlUMUc0VVBLTVQ3SU5YTDZJOTlSUDFKQUhFVi4u)

### II. `bash` Scripting (worth 50% of total exam grade)
Complete the following Exam 1 activities using bash code. It is assumed that your will be in your Exam 1 repo directory and that files will not be moved unless specified. Pseudo code and output formatting is provided, but you must modify it into real bash code to get full credit.

1. Clone your repository for this exam to your local computer.

2. Create a file called `exam1_solutions.sh` in your exam repository to record your answers in the form of a script.  

3. Take a snapshot of the changes to your Exam 1 repo dir using `git` by adding and committing your changes.

	* everytime after this, when you are asked to "take a snapshot", it means to `add` and `commit` the changes.  You can `push` if you want, but it is not necessary until you submit.  I like to `push` because it remotely backs up my work on github.

4. Using `notepad++` or `bbedit`, on line 1 of `exam1_solutions.sh`, add a `bash` shebang!.  

5. With the Buzzard et al 2015 data set, use bash commands to determine which species occurs in the most plots (and is thus the most widespread).
	Your code should return output as follows:
	```bash
	$ code to isolate the species observed in the most plots 
	Genus species
	```
	
	* On line 3 of `exam1_solutions.sh`, *copy and paste* this question (5. In the Buzzard ... most plots.) and make it a comment
	* On line 4 of `exam1_solutions.sh`, copy and paste your working line of code (do not indent).
	* Save the changes you made to `exam1_solutions.sh` then take a snapshot of your Exam 1 repo dir with git.

6. Copy and modify your line of code from question 5 to save the output into a variable named `MostWidespreadSpecies`

	* Do not change line 4
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

### III. Extra credit (worth 50% of total exam)
Use what you have learned to write a bash script that converts the Buzzard et al (2015) data set to a comma delimited tidy data file with each row being a unique species in the Buzzard et al. (2015) data set, and the columns being the species, the number of plots, the total number of individuals, total biomass, and total basal area for each species.  Use git for version control

### IV. Use git to submit your exam by pushing it back to your Exam 1 repo on GitHub.
