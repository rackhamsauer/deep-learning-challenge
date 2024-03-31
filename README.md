# deep-learning-challenge
I used previous examples, students, tutors, chat gpt and stack overflow to complete this assignment. Module 21 Write up 
Stacie Sauer-Rackham

Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis was to determine applicants that would have the best chance of success if given funding.
1.	Results: Using bulleted lists and images to support your answers, address the following questions:
•	Data Preprocessing
o	What variable(s) are the target(s) for your model?
	Target variable is the IS_SUCCESSFUL column.
o	What variable(s) are the features for your model?
	All other columns that are not IS_SUCCESSFUL.
o	What variable(s) should be removed from the input data because they are neither targets nor features?
	Both the EIN and the NAME columns were dropped from the data.
•	Compiling, Training, and Evaluating the Model
o	How many neurons, layers, and activation functions did you select for your neural network model, and why?
	The first attempt I used 8 hidden layers in the 1st, and 5 hidden layers in the second. They were just random numbers I chose.
o	Were you able to achieve the target model performance?
	I was not able to achieve the targeted 75% performance, even after 4 attempts.
o	What steps did you take in your attempts to increase model performance?
	I added more layers, added and removed hidden nodes, changed the amount of epochs trying to get additional accuracy.
3.	Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
This deep learning model was around 73% accurate in predicting. I would not recommend using any of these models to solve this problem. It could be possible to have a higher accuracy in the model if additional data clean up, activation functions and just taking the time to iterate until higher accuracy was reached.

