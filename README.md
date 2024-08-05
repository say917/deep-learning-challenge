# deep-learning-challenge

The report should contain the following:

# Overview of the analysis:

In the homework, I have been tasked at using a deep learning to create a classification model that can predict if a dataset will be successful based on target data and features. The dataset contains over 34,000 charities and I will use machine learning to create these models. 

# Results:
Using bulleted lists and images to support your answers, address the following questions:

# Data Preprocessing

What variable(s) are the target(s) for your model? n/
The target variable is the y variable. This holds the IS_SUCCESSFUL data. We want to know the data that was successful in the alphabet soup dataset
What variable(s) are the features for your model? 
The features for the model is the x variable. This holds the APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION',
 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS'
What variable(s) should be removed from the input data because they are neither targets nor features? 
We removed the 'EIN' and 'NAME' from the input data.

# Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? 

During my first optimization model I used 2 hidden layers with 80 and 30 neurons with a relu activation. The output layer was the sigmoid activation. Since the data appears to be nonlinear I decided to use the relu activation for my 2 hidden layers.

![image](https://github.com/user-attachments/assets/8d1119c1-68d9-4c01-8b45-db7d92b89767)

During my second optimization model I used 3 hidden layers all with 50 neurons with a relu activation. The output layer was the sigmoid activation. With the addition of the third layer I wanted to increase the number of neurons and connections. This increases the capacity to learn patterns and representations in the data.

![image](https://github.com/user-attachments/assets/c0a83696-39cb-4e3d-8679-da1ff276d157)

During my third optimization model I used 3 hidden layers all with 50 neurons with a tanh activation. The output layer was the sigmoid activation. The tanh activation function is used in neural network models for its ability to center the data, introduce non-linearity, and provide symmetric gradients. It is generally preferred over sigmoid due to its better gradient flow properties

![image](https://github.com/user-attachments/assets/d72a9fbe-8dd6-47fa-a50c-d310c2e3d6ae)


Were you able to achieve the target model performance? 
I was unable to achieve the target model performance. The highest accuracy I received was .7270
What steps did you take in your attempts to increase model performance? 
The highest accuracy I received was during my first optimization. I added an additional hidden layerand I reduced the neurons from to 80 to 50

# Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
