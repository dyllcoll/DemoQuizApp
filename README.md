# DemoQuizApp README

# Description: 

This is a simple interactive quiz application built using HTML, CSS, and JavaScript. The app features a timer-based quiz where users have to answer questions within a time limit. It tracks their score and displays a result at the end of the quiz.

# Features

Timed Quiz: Each question has a 15-second timer.

Interactive UI: The quiz interface is interactive, with start, quit, and restart options.

Score Calculation: Users receive points based on the number of correct answers.

Result Display: At the end of the quiz, users are shown their score and a crown icon indicating the completion.

# Technologies Used

HTML: Structure of the app.

CSS: Styling the app with responsive design.

JavaScript: Logic for quiz functionality, including dynamic question and option insertion, timer, and scoring.

# File Structure

# DemoQuizApp
   |
   | - css                # CSS folder
   |   |-- style.css
   |
   | - js                 # JavaScript folder
   |   |-- questions.js   # This consists of multiple quesitons each with one correct answer and three wrong answers.
   |   |-- quizApp.js     # This consists of the timer, button functions, and score.
   | 
   | - .gitignore         # This file is empty im not sure why.
   | - index.html         # This is the landing page that creates all of the visual elements.

# Setup Instructions

How to clone this repository to your local machine.

git clone https://github.com/your-username/DemoQuizApp-master.git

Open index.html in your browser to start the quiz.

Optionally, open the project in a text editor to modify the quiz questions or styling.

# How It Works

When the user clicks "Start Quiz", the quiz begins with a timer for each question.

The user selects an answer from the provided options. Once a selection is made, it cannot be undone.

The timer counts down from 15 seconds, and once time runs out, the user cannot select an answer.

At the end of the quiz, the user's score is displayed, and they have the option to replay the quiz or quit.


# How to add more questions

# Step 1
Find how many questions are currenrently in the app.
# Step 2 
Get your question and answers ready.
# Step 3
Go to the questions.js file and place your new question object in the questions array
# Step 4
It should look like this 
{
    numb: 6,
    question: "What does .py stand for?",
    answer: "Python File",
    options: [
      "JavaScript File",
      "Python File",
      "Moodle File",
      "Word Document File",
    ],
  },

# You can create as many questions and answers as you want just make sure to 
# assign the correct number for the question.



# Contributing

Feel free to email me dylancollins@oakland.edu with any bugs or issues!

# License

This project is licensed under Oakland University CSI 3150 F24

