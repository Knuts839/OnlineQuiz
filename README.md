README.MD
Link to deployed application: https://knuts839.github.io/CodingQuizRepo/

The purpose of assignment 4, the code quiz project is to create a coding assessment tool that a fullstack developer might encounter in an interview. Hopefully this tool will help developers become familiar with such assessments. 

This coding quiz project will beigin with a paragraph explaining the rules of the quiz to the quiz taker and start button to begin the quiz. This quiz will be a 75 second timed quiz containing a series of multiple choice questions. After the start button is clicked the paragraph and the start button will disappear and the timer will be displayed in the upper-right corner and a link to view the high scores will be displayed at the top left corner and the first multiple choice question will be displayed. Answering a question automatically displays whether you are correct or incorrect for 2 seconds, after which the next question is displayed. If the question previously answered was incorrect 10 seconds is removed from the timer. The test is over when all questions have been answered or there is no time remaining. The score of the test is the amount of time remaining or zero if none remains. When the test is over the screen will indicate that the test is done and the final score is displayed. The user may enter their initials and click the save button. The next screen a list of the high scores, a go back button and a clear high scores button. If the user clicks on the clear high scores button the high score items in the json file will be removed and the page will refresh and display accordingly. If the user clicks the go back button it will take them to the beginning of the quiz. 

The above paragraph attempts to describe everything seen in the mockup and acceptance criteria. Below is a list of the items in the acceptance criteria and mockup I was not able to complete in the time alotted for this assignment. 

I completed everything in the acceptance criteria below are the three items I did not complete from the mockup.
The mockup included a link to include high scores. I did not implement this feature from the mockup.
While I do display whether or not the previous answer was correct, I did not remove it after 2 seconds as specified by the mockup. 
I did not create a list of high scores as specified by the mock up however I do save your score to local storage.
