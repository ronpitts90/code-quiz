# code-quiz
quiz hw
This breif quiz was created to test the basic knowledge of HTML,CSS, and JS.

GIVEN I am taking a code quiz 
WHEN start button is clicked THEN a timer starts and as well as the quiz
WHEN one questions is answered then the the quiz oves to the next question
WHEN I answer a question incorrectly THEN time is subtracted from the clock WHEN all questions are answered or the timer reaches 0 
THEN the game is over 
WHEN the game is over THEN I can save my initials and score

To begin with, created everything needed for the html page such as divs and links.

I used button createElement functions to create button in my javascript code.

I used setInterval function to create timer and clear interval to stop the timer when the quiz is over.

i used a remove element to remove buttons as we proceed with the quiz and create new buttons simaltaneoulsy.

A correct and wrong functon was called to subtract time and add score at the end.

Each time you select an answer either correct or wrong function is initiated to add score or reduce time from the quiz.

I called postquiz function to put my initials and score to local storage so i can recall it later at the score page.
