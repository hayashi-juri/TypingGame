# TypingGame
<img src = "https://github.com/hayashi-juri/TypingGame/blob/main/typing%20game/typing_game.png" width="300px"><br>
[demo](https://github.com/hayashi-juri/TypingGame/issues/1#issue-2402584442)

The referenced code has been extended to implement the following features<br>
References: https://www.sejuku.net/blog/143146<br>

- Show timer function
- Wrong spellings are indicated in red
- Repeat until correct typing is achieved
- Displays percentage of correct answers and speed after completion

## detail
1. Countdown timer:
- Modify the startCountdown function to count down repeatedly until the user enters the correct input.

2. Error indication:
- Use the highlightDifference function to highlight wrong characters in red.

3. Percentage of correct answers and typing speed:
- Tracks totalAttempts and correctAttempts and displays the percentage of correct answers and average typing speed after 5 typing attempts.
- The displayResults function calculates and displays the results.
  
4. Input checks:
- Checks user input with the checkInput function, displays next word if correct, and displays results after the fifth typing is completed.

5. Event Listeners:
- The checkInput function is called on button click and enter key press events.

6. Tracking first input:
- Introduce a boolean variable called firstAttempt to track the first input for each word.

7. Calculate correct answers:
- Update totalAttempts and correctAttempts based on first input.

8. Input Checking:
- Checks if the initial input is correct and affects the correct rate.
- After the initial input is complete, the input is repeated until the user inputs correctly.
