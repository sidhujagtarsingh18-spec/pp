# pp
##  NAME AND DESCRIPTION
"PROJECT NAME" - SENTIMENT ANALYSIS ON TEXT 
"DESCRIPTION:" - THIS PROJECT ANALYSES SHORT TEXT ( LIKE REVIEWS OR COMMENTS) AND PREDICTS WHETHER THE SENTIMENT IS "POSITIVE" OR "NEGATIVE".

##SUMMARY:-
  SENTIMENT ANALYSIS PROJECT
THIS REPOSITORY IS CREATED AS A PART OF THE "GROW WITH GOOGLE - LEARN BASICS OF AI" COURSE.
IT DEMONSTRATES A SIMPLE ARTIFICIAL INTELLIGENCE PROJECT USING TEXT SENTIMENT ANALYSIS.
-----------------------

##  BACKGROUND
ARTIFICIAL INTELLIGENCE IS WIDELY USED IN UNDERSTANDING HUMAN LANGUAGE . COMPANIES LIKE AMAZON, NETFLIX, AND GOOGLE USE SENTIMENT ANALYSIS TO KNOW WHAT USERS FEEL ABOUT THEIR PRODUCTS OR SERVICES.
THIS PROJECT IS A VERY SIMPLE VERSION OF THAT . 
-------------

##  DATA AND AI TECHNIQUES
- "DATA":- A SMALL SET OF EXAMPLE SENTENCES (E.G., "I LOVE THIS MOVIE"- POSITIVE ,  " I HATE WAITING" - NEGATIVE" )
- "AI TECHNIQUE:" - RULE BASED TEXT CLASSIFICATION (USING SIMPLE KEYWORDS LIKE "GOOD, HAPPY, LOVE, HATE, BAD ").
  > SINCE THIS IS A BEGINNER PROJECT, WE ARE NOT USING BIG MACHINE LEARNING MODELS FOR DATASETS.
--------------

##  HOW IT IS USED 
-USER ENTERS A SENTENCE  (E.G.,  *” THE FOOD WAS GREAT”*).
- THE PROGRAM CHECKS FOR POSITIVE OR NEGATIVE WORDS.
- IT OUTPUTS WHETHER THE SENTIMENT IS **POSTIVE ** OR ** NEGATIVE


# Simple Sentiment Analysis Program for AI Course Project


def analysis_sentiment(text):
    postive_words = ["good","great","happy","love","excellent"]
    
    negative-words = ["bad","terrible", "sad","hate","angry"]


    text = text.lower( )
    score = 0
    

    for word in positive_words:
       if word in text:
	score += 1

    for word in negative_words:
      if word in text:
      score -= 1

  

     if score > 0:
      return "Positive"
     
     elif score< 0:
      return "Negative"

     else:
     return "Neutral"
--------------

##   Challenges or Limitations
-	Only works with small, simple sentences.
-	Cannot handle sarcasm or complex text.
-	Uses basic keyword matching (not advanced ML or Deep learning.)
------------

##  What  next
-	Use a large dataset of reviews or  tweets.
-	Train a machine learning model ( like Naïve Bays or Logistic Regresssion).
-	Improve accuracy with Natural Language Processing (NLP) techniques.

--------------
##  Acknowledgement
This project was created for the  ** Grow with Google- Learn Basics of AI Course**.
Special thanks to the course instructors and resources that guided this learning journey.
--------------

  
