# deep-learning-challenge

The report should contain the following:

# Overview of the analysis:

Explain the purpose of this analysis.

# Results:
Using bulleted lists and images to support your answers, address the following questions:

# Data Preprocessing

What variable(s) are the target(s) for your model? The target variable is the y variable. This holds the IS_SUCCESSFUL data. We want to know the data that was successful in the alphabet soup dataset
What variable(s) are the features for your model? The features for the model is the x variable. This holds the APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION',
 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS'
What variable(s) should be removed from the input data because they are neither targets nor features? We removed the 'EIN' and 'NAME' from the input data.

# Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? 

During my first optimization model I used 2 hidden layers with 80 and 30 nuetrons with a relu activation.

![image](https://github.com/user-attachments/assets/8d1119c1-68d9-4c01-8b45-db7d92b89767)

Were you able to achieve the target model performance? I was unable to achieve the target model performance. The highest accuracy I received was .7270
What steps did you take in your attempts to increase model performance? The highest accuracy I received was during my first optimization. I added an additional hidden layerand I reduced the neurons from to 80 to 50

# Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
