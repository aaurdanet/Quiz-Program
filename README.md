# Quiz-Program
Description:
This repository contains a simple quiz program where questions are presented to the user, and they are prompted to provide answers. The program evaluates the answers and provides feedback to the user along with the final score.

Files:

  quiz.py: This file contains the main logic for running the quiz program. It creates a list of questions, presents them to the user, checks the answers, and calculates the final score.

  question_data.py: This file contains a list of predefined questions in JSON format. It serves as a data source for the quiz program.

  question_model.py: This file defines the Question class, which represents a single question in the quiz.

  quiz_brain.py: This file defines the QuizBrain class, which manages the flow of the quiz, including presenting questions, checking answers, and calculating the score.

Usage:

  Running the Quiz:
      Run quiz.py to start the quiz program.
      Follow the prompts to answer each question.
      After completing the quiz, the program will display the final score.

Dependencies:

  This code requires Python 3.

Note:

  Ensure that you have all the required files (question_data.py, question_model.py, quiz_brain.py) in the same directory as quiz.py before running the program.
  You can modify the questions in question_data.py or add your own questions to customize the quiz.
