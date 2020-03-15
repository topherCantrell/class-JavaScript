# Exercise 2: Application Project

## From: Lesson Summary Section 4

### Project 2

Next, create another XHTML page with a `<script>` block in the `<head>` section of the
document. This script should include the following:
  * Create a function named `whileTest()`. Inside the function, create a variable named
number and assign it a value between 1 and 10.
  * Create another variable named `answer` and assign it a value of 0 (zero).
  * Then create a `while` loop. Create code that will cause the loop to execute as long
as the `number` variable does not equal the answer variable.
  * Inside the loop, assign the `answer` variable the return value from a prompt dialog
box.
  * The prompt will ask the user to guess a number between 1 and 10. The loop will
continue until the proper answer is entered.
  * After the loop exits, use an alert dialog box to inform the user of a correct guess.
  * Once you have the code working properly, create code that will allow the user
only three guesses. If, after three guesses, the user has not entered the correct
answer, exit the function and alert the user that he or she is out of guesses via an
alert dialog box.
  * Ensure that only one dialog box appears after the function is exited, one with a
correct guess message, or one asking the user to try again.
  * Experiment with different methods that you have seen for calling the function.
You can use the `load` event or the `onclick` event handler of a form button.