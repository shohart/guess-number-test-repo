# Project 1. Task 8.1 of SkillFactory python course.

## Table of contents  
[1. Project description](.README.md#Project_description)  
[2. Which case do we solve?](.README.md#Which_case_do_we_solve?)  
[3. Data summary](.README.md#Summary-data)  
[4. Project stages](.README.md#project-stages)  
[5. Result](.README.md#Result)    
[6. Summary](.README.md#conclusions) 

### Project description

Guess the number the computer guessed in the minimum number of tries possible.

:arrow_up:[to table of contents](_)


### What kind of case are we solving?    
You have to write a program that guesses the number in the minimum number of tries.

**Conditions for the contest:**  
- The computer guesses an integer from 0 to 100, and we have to guess it. By "guess", we mean "write a program that guesses the number".
- The algorithm takes into account information about whether a random number is greater or less than the number we want.

**Quality metrics**.     
Results are estimated by the average number of attempts at 1000 repetitions. Number of tries shold be less than 20. 

**What we practice**     
Learning to write good code in python


### Data summary
No additional data used in this project.
  
:arrow_up:[to table of contents](.README.md#Table_of_contents)


### Stages in the project  
- First we need to write a function to guess an integer, usin the info wheter random number is bigger or less than the number we want. We can use function from project 0, but instead of printing a tip for the user we can adjust algorithm's logic.
- Second we need to write a function to rate results of our project to be sure that it fulfills the conditions.
- Then we need to check our code if it maches PEP standarts.
- Finally we need to upload a code to GitHub and make shure that GitHub is designed accordingly (includind documentation, file structure, code repeatability, etc).

:arrow_up:[to table of contents](.README.md#Table_of_contents)


### Results:  
We got an algorithm that fulfills conditions and can guess an integer in 5 tries average. We froze requirements using pip in requirements.txt.

Function **random_predict_midl()** can be used with a set up integer or can calculate a random number by itself. Thus it has built in protection to check whether provided number is in range.

Function **score_game_midl()** runs predict function 1000 times and return average function result.  

Task conditions are fulfilled.

:arrow_up:[to table of contents](.README.md#Table_of_contents)


### Conclusions:  
....

:arrow_up:[to table of contents](.README.md#Table_of_contents)


If you find the information on this project interesting or useful I would be very grateful if you would mark the repository and profile ⭐️⭐️⭐️- by Shohart (with SkillFactory)