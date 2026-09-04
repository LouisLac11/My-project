# World Capitals Trainer
## The context

Many learners are familiar with country names but struggle to recall their capitals. Geography education often relies on rote memorization, which can become monotonous and lacks interactivity. This initiative suggests a straightforward educational approach: a geography quiz created using Python.

The goal of the program is to assist users in enhancing their understanding of countries and their capitals in a more engaging manner. Instead of simply reviewing a list of countries alongside their capitals, the user participates by answering questions and receiving immediate feedback. This approach makes the learning experience more dynamic and enables users to recognize the countries they are already familiar with and those requiring more practice.

This project is also beneficial from a coding standpoint, as it incorporates several basic Python concepts within a practical context. The program will utilize variables, conditional statements, loops, lists or dictionaries, user input, random question generation, counters, and score tracking.

## What the Program Will Do

Upon starting the program, a welcome message will be shown, along with an explanation of the quiz's goal. The user will then select a difficulty level:

* **Easy:** familiar countries and well-known capitals, like France–Paris or Mexico–Mexico City.
* **Medium:** less familiar countries and capitals, such as Canada–Ottawa or Australia–Canberra.
* **Hard:** more challenging countries and capitals from various regions around the globe.

Once the difficulty level is chosen, the program will randomly select a specific number of questions from a database containing countries and their capitals.

For each question, the program will:

1. Present the name of a country.
2. Request the user to type in its capital.
3. Compare the user’s response with the correct answer.
4. Show a message indicating if the response is right or wrong.
5. If the answer is wrong, reveal the correct capital.
6. Increase the score by one point for each correct answer.
7. Move on to the next question.

Upon completion of the quiz, the application will compute and present:

* The total number of correct responses.
* The overall amount of questions posed.
* The percentage of answers that were correct.
* A concluding message that reflects the user's performance.

For instance, if a participant answers 8 out of 10 questions correctly, the application might show:

**Final Score: 8/10 – 80%**

It may also include a message like:

**“Excellent work! You possess a solid understanding of world capitals.”**

The primary goal of this project is to develop a straightforward yet comprehensive educational game that enables users to assess and enhance their geographical knowledge while showcasing essential Python programming principles.
