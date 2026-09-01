# World Capitals Trainer
## The context

Many students know the names of countries but have difficulty remembering their capitals. Geography is often learned by memorizing information, which can become repetitive and not very interactive. This project proposes a simple educational solution: an interactive geography quiz developed in Python.

The purpose of the program is to help users improve their knowledge of world countries and capitals in a more engaging way. Instead of only reading a list of countries and capitals, the user actively answers questions and immediately receives feedback. This makes the learning process more dynamic and allows the user to identify the countries they already know and the ones they need to practice more.

This project is also useful from a programming perspective because it applies several fundamental Python concepts in a practical situation. The program will use variables, conditional statements, loops, lists or dictionaries, user input, random questions, counters, and score calculations.

## What the Program Will Do

When the program starts, it will display a welcome message and explain the objective of the quiz. The user will then choose a difficulty level:

* **Easy:** common countries and well-known capitals, such as France–Paris or Mexico–Mexico City.
* **Medium:** less obvious countries and capitals, such as Canada–Ottawa or Australia–Canberra.
* **Hard:** more difficult countries and capitals from different regions of the world.

After the difficulty level is selected, the program will randomly choose a certain number of questions from a database of countries and capitals.

For each question, the program will:

1. Display the name of a country.
2. Ask the user to type its capital.
3. Compare the user's answer with the correct answer.
4. Display a message indicating whether the answer is correct or incorrect.
5. If the answer is incorrect, display the correct capital.
6. Add one point to the score when the answer is correct.
7. Continue with the next question.

At the end of the quiz, the program will calculate and display:

* The number of correct answers.
* The total number of questions.
* The percentage of correct answers.
* A final message depending on the user's performance.

For example, if the user answers 8 questions correctly out of 10, the program could display:

**Final Score: 8/10 – 80%**

It could also display a message such as:

**“Great job! You have a good knowledge of world capitals.”**

The main objective of the project is therefore to create a simple but complete educational game that allows users to test and improve their geography knowledge while demonstrating the use of fundamental Python programming concepts.
