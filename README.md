# SI-206-HW4
SI 206 Data-Oriented Programming

Homework Name: Unit Testing

Homework Objective:
Demonstrate the ability to:
Complete partial unit tests
Create unique unit test
Background:
In order to complete this assignment you will need to familiarize yourself with the Card class covered in lecture.  You will also want to review any readings on Unit Testing in Python.

Then you will include tests for the cases described below.  There are a few notes though:
You may create as many or few unittest.TestCase subclasses as you like. 

You must arrange your code so that if you were to fail a test, that would not cause any other tests to fail as a result of that test failing. 

IF YOU INVOKE THE play_war_game FUNCTION IN A TEST CASE, YOU MUST INVOKE IT WITH THE PARAMETER testing=True, like this:
play_war_game(testing=True) AS OPPOSED TO play_war_game()
If you do not do that, we will not be able to grade your homework properly!

You may assume that other programmers will NOT invoke these functions with unacceptable inputs (e.g. no one will try to create a card with rank 0). You just need to ensure that the code works as intended.

Steps:
Test that if you create a card with rank 12, its rank will be "Queen"

Test that if you create a card with rank 1, its rank will be "Ace"

Test that if you create a card instance with rank 3, its rank will be 3

Test that if you create a card instance with suit 1, it will be suit "Clubs"

Test that if you create a card instance with suit 2, it will be suit "Hearts"

Test that if you create a card instance, it will have access to a variable suit_names that contains the list ["Diamonds","Clubs","Hearts","Spades"]

Test that if you invoke the __str__ method of a card instance that is created with suit=2, rank=7, it returns the string "7 of Hearts"

Test that if you create a deck instance, it will have 52 cards in its cards instance variable

Test that if you invoke the pop_card method on a deck, it will return a card instance.

Test that the return value of the play_war_game function is a tuple with three elements, the first of which is a string. (This will probably require multiple test methods!)

 (and 12)  Write at least 2 additional tests (not repeats of the above described tests). Make sure to include a descriptive message in these two so we can easily see what you are testing!

