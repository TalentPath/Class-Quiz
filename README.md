# Class-Quiz Builder
Create a terminal based quiz builder with different types of questions


Using JavaScript Classes, build a terminal based quiz that takes input to build a quiz and outputs the quiz after the user is done building it

Your application should have:
* a parent class for overall Quiz questions
* child or sub classes based on that parent class for question types 
  * Multiple Choice  (has multiple available answers)
  * True False    (has only 2 available answers)
  * Direct    (has just one answer)


In the creation of each new question you should as the user the following questions:
* What type of question would you like to create
* What is the question
* What is/are the available answers
* What is the correct answer

Based off of the user response, create a question object based off of the class definition for the appropriate question type and store this in an array.

After each created question as the user if they would like to create a new question

if they respond yes, allow them to create a new question using the prompts above
if they respond no, output the questions array to the console in an easy to read format

