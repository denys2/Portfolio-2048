1. Replace `<your_account>` with your Github username in the link
    - [DEMO LINK](https://denys2.github.io/js_2048_game/)
2. Follow [this instructions](https://mate-academy.github.io/layout_task-guideline/)
    - Run `npm run test` command to test your code;
    - Run `npm run test:only -- -n` to run fast test ignoring linter;
    - Run `npm run test:only -- -l` to run fast test with additional info in console ignoring linter.

## 2048 Game

### Project Presentation

Hello there! Welcome to my 2048 Game project, a testament to my JavaScript proficiency. Let me walk you through the exciting features and challenges that this project encapsulates. [this reference](https://play2048.co/)
Project Overview
This project is a recreation of the classic 2048 game, showcasing my adeptness in JavaScript. The game adheres to specific rules and requirements, providing a challenging yet enjoyable experience for users.

Key Instructions
Test Your Skills: Follow the DEMO LINK to experience the game firsthand.
Run Tests: Execute npm run test to run comprehensive tests on the code.
Fast Testing: Use npm run test:only -- -n for quick tests, ignoring the linter.
Informative Testing: Employ npm run test:only -- -l for detailed tests with additional console information, ignoring the linter.
Project Features
1. Game Mechanics
The game field is a 4x4 grid.
Cells may contain numbers: 2, 4, 8, ..., 2^n.
Players move cells using keyboard arrows.
Numbers merge when two equal cells meet, doubling the value.
Merged cells cannot merge again in the same move.
2. Gameplay Elements
Valid moves fill empty cells.
After each move, a 2 or 4 appears randomly in an empty cell.
A win message displays when the player reaches the coveted 2048 value.
The game over message appears when no more moves are available.
3. User Interface
The start message hides upon game initiation.
The Start button transforms into Restart after the first move.
Score increments with each move, totaling the sum of merged cells.
4. Visual Enhancements
Styling utilizes the field-cell--%cell_value% class for visual appeal.
Elements are strategically hidden using the hidden class.
The main button features distinct styles with start and restart classes.

![Project Preview](./src/images/reference.png)
