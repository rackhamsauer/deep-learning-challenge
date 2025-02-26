# deep-learning-challenge
Neural Networks Write Up - Stacie Sauer-Rackham
This repository contains the analysis and work completed for Module 21, where the goal was to develop a deep learning model to predict which applicants have the best chance of success if given funding. The analysis involved preprocessing the data, building and evaluating a neural network model, and drawing conclusions about model performance.

Overview of the Analysis
The purpose of this analysis was to identify the applicants most likely to succeed if provided funding. A deep learning model was created using the provided data, with the target variable being the IS_SUCCESSFUL column, and all other columns being used as features. The model was built, trained, and evaluated to determine its performance, with the goal of achieving at least 75% accuracy.

Results
Data Preprocessing
Target Variable:
The target variable used for the model is the IS_SUCCESSFUL column, which indicates whether an applicant was successful.

Feature Variables:
All other columns, excluding the target variable, are considered feature variables. These include various details about the applicants that help determine their likelihood of success.

Variables to Remove:

The EIN and NAME columns were dropped from the data, as they do not contribute useful information for predicting success.
Compiling, Training, and Evaluating the Model
Neurons, Layers, and Activation Functions:

In the first attempt, I used 8 hidden layers in the first model and 5 hidden layers in the second model. These were random choices, with the goal of testing various configurations.
The activation functions used for the hidden layers and output layer were selected to test basic configurations, as I aimed to determine the best model architecture through trial and error.
Model Performance:

Despite several attempts, I was not able to achieve the target model performance of 75% accuracy. After four attempts, the highest achieved accuracy was around 73%.
Steps to Improve Model Performance:

To try and improve accuracy, I added more layers, adjusted the number of hidden nodes, and changed the number of epochs in each attempt. However, these adjustments did not result in the desired performance improvement.
Summary
The deep learning model was able to achieve an accuracy of approximately 73%, which was just short of the target of 75%. While the model showed potential, it did not meet the performance goal, and further improvements would be necessary to achieve better results.

Recommendation
Given the current results, I would not recommend using this deep learning model as the solution for this classification problem. However, it might be possible to achieve higher accuracy with additional data cleanup, experimenting with more sophisticated activation functions, and allowing for more iteration on the model design and training process. Alternatively, exploring other machine learning models such as Random Forests or Gradient Boosting might yield better results, as these models often perform well on classification tasks without the need for extensive tuning.

Tools and Resources Used
TensorFlow / Keras for building and training the deep learning model.
Python for scripting and data manipulation.
ChatGPT, Stack Overflow, and peer support for problem-solving and debugging during the process.
Previous class lessons for guidance on building neural networks and understanding model performance evaluation.
How to Use
Clone the repository to your local machine.
Ensure you have Python, TensorFlow, and other necessary libraries installed.
Open the Jupyter Notebook or Python script to review the model, data preprocessing steps, and evaluation.
Experiment with model configurations and data preprocessing to attempt improving accuracy.

