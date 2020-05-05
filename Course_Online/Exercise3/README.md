# Exercise 3: Application Project

## From: Lesson Summary Section 7

## Application Project


This project will challenge you to use some of what you have learned in this lesson.

This small application will present the user with an XHTML page containing a form that
simulates a credit card number submission form. This form has been created for you
and is named `lesson7AppProject.htm`. This file is located in the Lesson_7 directory.

Your task is to add script to this file so that when a button is clicked, a script will perform
validation tests. For instance, test with script to see whether the expiration date is valid.
If it is not, prompt the user to update that field in the form.

Test the digits entered in the Card Number field to see whether they are valid for the
type of credit card selected at the top of the form. For ex ample:
  - Visa card numbers always begin with the numeral 4 and use 16 digits.
  - MasterCard numbers always begin with the numeral 5 and use 16 digits.
  - American Express card numbers always begin with the numeral 3 and use 15
digits.

If the numbers are incorrect based on the card type selected, ask the user to either
select a different credit card or change the card number. If the number of digits
corresponds correctly, acknowledge that.

Note that you are not expected to create an algorithm sophisticated enough to actually
verify credit card numbers. However, creating the logic to perform the task previously
described will strengthen your understanding of JavaScript when used to interact with
user-submitted information.