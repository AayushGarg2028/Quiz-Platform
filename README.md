# KBC Quiz System (Kaun Banega Crorepati) - Console Application

## Description
This is a console application for the popular Indian quiz show "Kaun Banega Crorepati" (KBC). The application allows users to play a quiz game, manage questions, and keep track of scores.

## Features
- Admin functionality to manage quiz questions.
- Student mode to play the quiz.
- Question management includes adding, updating, and deleting questions.

## Prerequisites
Make sure to have a C compiler installed on your system.

## Build & Run Instructions
1. Clone the repository.
2. Navigate to the project directory.
3. Compile with: `gcc main.c -o kbc_quiz`
4. Run with: `./kbc_quiz`

## File Format for ques.txt
Each question is formatted in 8 lines:
1. Question text
2. Option A
3. Option B
4. Option C
5. Option D
6. Correct option (A/B/C/D)
7. Timeout (in seconds)
8. Prize money

## Security Note
Ensure that the application is run in a controlled environment. Carefully manage access to the admin functions.

## Contributing
Contributions are welcome! Please open an issue or pull request for any improvements or suggestions.

## License
This project is licensed under the MIT License.