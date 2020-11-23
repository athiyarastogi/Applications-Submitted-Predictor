
   <img src="https://user-images.githubusercontent.com/47875071/99720236-76f45480-2a7b-11eb-8387-2a1dd3e9818e.png" width="50"> 
   
# Applications Submitted Predictor
> Predict number of applications submitted based on applications created and forms downloaded.

![Python 3.7.4](https://img.shields.io/badge/Python-3.7.4-brightgreen.svg) ![license MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg)


# Table of Contents
 Purpose  
 
 Compatibility
 
 Functionality and Screenshots 
 
 Assumptions
 
 Use Cases
 
 Future Goals


# Purpose

Applications Submitted Predictor is designed to predict 'Number of Applications Submitted' based on 'Applications Created' in a system and  'Application forms downloaded'. It was originally built in order to automate the prediction of applications submitted, for employees who use SEIBEL CRM (software to send, manage and receive grants) to track applications and their status to make business decisions, However, it can be used whenever a prediction has to be made regarding the number of applications that will be submitted.


# Compatibility

The following code is compatible with Python 3.6 on Windows, Mac OS, and Linux.


# Functionality and Screenshots

After running the program, the window pictured below is displayed.

<img src="https://github.com/athiyarastogi/Applications-Submitted-Predictor/blob/main/Screen%20Shot%202020-11-22%20at%206.37.44%20PM.png"> 


# Input and Output


#### Number of Applications Created

The Number of Applications Created widget is for inputting the number of applications created by users in total.

#### Number of forms Downloaded

The Number of forms Downloaded widget is for inputting the number of applications forms downloaded by the users for their inidividual applications, in total. FOrms could be downloaded multiple times for a single application. Therefore, Number of forms Downloaded could exceed the Number of Applications Created.

#### Predict the number of Applications Submitted

The code used the above two - Number of Applications Created and Number of forms Downloaded to predict the number of Applications Submitted.


# Assumptions

The code has been written keeping in mind the following assumptions

   ### a)
   If the Number of Applications created is 0, then the Applications submitted will be 0, regardless of the value of the intercept or the number of application forms downloaded.
   
   ### b)
   If the Number of Application forms downloaded is 0, then the predicted value for Applications Submitted automatically becomes 0.
   
   ### c)
   The predicted Number of Applications Submitted cannot exceed the Number of Applications Created.
   
   
   
# Use Cases

 This current use case for this program is to predict the number of applications submitted based on the applications created in the system and the number of relevant material(s) user downloads for that application. 
 
 
 #  Future Goals
 
 For the future the user will be able to check the accuracy percentage for each prediction done through this program.
   
