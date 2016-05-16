# smsQuizApp

##Description
A test article that was in production for the RIT Media Sciences app. It was never finished and is only in a testing stage.

The purpose of this article is to give a short quiz to a user and then, based on their answers, give them a recommendation about what kind of student they would be in our program (based on the 'paths' that are finalized by the faculty). There is a results page that gives a description of their student type and then displays a list of possible classes from our major that fit their student type.

##Article Status
- Article was never published on the RIT Media Sciences app.

##Code Status 
1. On the current end screen of the quiz we show the student a 'path' in our major and description of what type of student they are based on their answers. Right now there is only one 'path' and description that gets shown to the user, regardless of their answers. We would need to come with appropriate 'paths' that students could take in our major that fit what the faculty agree upon, and accompanying descriptions.

2. Along with the 'path' and description that we show a user when they complete the quiz, we also show the top 5 classes that match the selected answers that the user chose. There is an actual 'classlist' data object and functions in the JS that calculate which classes to show based on the answers. The classes in the 'classlist' data object all have different weights for the 4 distinct 'paths' in our major (right now they are code, design, print, and management), but the weights were assigned by me based on what I thought the classes offered. Since the 4 paths will probably change, the weights of the classes and that entire 'classlist' object should be updated if someone works on this more.

3. The code is very much in the development stage, the visual elements of the article are just styled enough to be useable. Additionally the questions and answers in the article are just test content. We would need to come up with a set of questions and appropriate answers for the quiz that would determine which 'path' in our major is right for the user.

###Hayden's Recommendations
Steps if we want to use this are: 
  
  1. Solidify the different 'paths' or categories within our major (make sure we reach consensus with faculty and Shauna)
  
  2. Write data object to hold the 'paths' and descriptions that we show the users when they finish the quiz
  
  3. Rewrite the 'classlist' data object to reflect all offered classes and make sure their assigned weights match the new 'paths'
  
  4. Write the questions and different answers for the quiz portion of the article
  
  5. Finish styling the article and adding animation
  
