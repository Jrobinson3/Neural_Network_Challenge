# Neural_Network_Challenge
## Deliverable 1: Preprocessing Data for a Neural Network Model

Completed AlphabetSoupCharity.ipynb-Deliverable 1 is uploaded: https://github.com/Jrobinson3/Neural_Network_Challenge/blob/main/AlphabetSoupCharity.ipynb

![image](https://github.com/Jrobinson3/Neural_Network_Challenge/blob/main/Merged%20data.png)

## Deliverable 2: Compile, Train, and Evaluate the Model
Completed AlphabetSoupCharity.ipynb-Deliverable 2 is uploaded: https://github.com/Jrobinson3/Neural_Network_Challenge/blob/main/AlphabetSoupCharity.ipynb
Additionally exported AlphabetSoupCharity.h5 is uploaded: https://github.com/Jrobinson3/Neural_Network_Challenge/blob/main/AlphabetSoupCharity.h5
The results of performance accuracy is 72.59%.

![image](https://github.com/Jrobinson3/Neural_Network_Challenge/blob/main/model%20accuracy.png)

## Deliverable 3: Optimize the Model
Completed AlphabetSoupCharity_optimization.ipynb-Deliverable 3 is uploaded:https://github.com/Jrobinson3/Neural_Network_Challenge/blob/main/AlphabetSoupCharity_optimization.ipynb

Additionally exported AlphabetSoupCharity_optimizaiton.h5 is uploaded:https://github.com/Jrobinson3/Neural_Network_Challenge/blob/main/AlphabetSoupCharity_optimization.h5

## Deliverable 4: A Written Report on the Neural Network Model
![image](https://user-images.githubusercontent.com/89823576/155266422-78548132-b866-4b53-bcac-04fcafa72f48.png)

1. Overview of the analysis: Explain the purpose of this analysis.
Using machine learning and neural networks, to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funding by Alphabet Soup.

2. Results: Using bulleted lists and images to support your answers, address the following questions.
Data Preprocessing
What variable(s) are considered the target(s) for your model?
IS_SUCCESSFUL is considered the target for my neural model. 

What variable(s) are considered to be the features for your model?
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT,
SPECIAL_CONSIDERATIONS

What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and Name are neither targets nor features and these are removed from the input data. 

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
The number of input features and hidden nodes for each layer are below:
number_input_features = len(X_train[0])
hidden_nodes_layer1 = 100
hidden_nodes_layer2 = 50
To try to increase accuracy score, the best way to do this with increasing layers and changed second hidden layer to be "sigmoid" and output layer to be "relu".  Additionally reduced epochs to 50 from 100.

Were you able to achieve the target model performance?
it was improved from 72.17 to 72.59.  

What steps did you take to try and increase model performance?
To increase layers and reduced epochs to improve model performance accuracy.

3. Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

The results of the deep learning model using keras module is ideal and categorical variables canbe bucketed together and encoding.  Other model would take less time to tarin and predict values, the deep learning model required more time to train data points.  If other model predict values similar to deep learning model, you should use other model (i.g. random forest classifier) to save time. 


