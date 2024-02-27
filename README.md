# deep-learning-challenge
deep-learning-challenge

# Background

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively


# Analysis - Report:

Overview of the analysis:The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures.



# Data Preprocessing

	variable(s) "APPLICATION_TYPE","ORGANIZATION" and "INCOME_AMT" are the target(s) for your model.

	variable(s) "IS_SUCCESSFUL" (True/False) is the features for your model.

	variable(s) 'EIN', 'NAME', 'STATUS', 'SPECIAL_CONSIDERATIONS' and 'ASK_AMT' should be removed from the input data because they are neither targets nor features 



# Compiling, Training, and Evaluating the Model

T  wo Hidden layers, One Output layer is chosen to train model. 10 Neurons for each layer are chosen to train Neural network model.

  Since Relu is fast to train, "RELU" Activation Functions is used for Hidden layers and "sigmoid" function is used to output Neuron.  


# Results: 

After removing Non Beneficial fields: 'EIN', 'NAME', 'STATUS', 'SPECIAL_CONSIDERATIONS' and 'ASK_AMT' desirned performance is observed.

Model performance improvement is observed on each attept to train: 

First Attempt Results:  Loss: 0.5508238077163696, Accuracy: 0.7320116758346558
Second Attempt Results: Loss: 0.5480531454086304, Accuracy: 0.7327113747596741
Third Attempt Results:  Loss: 0.5592454671859741, Accuracy: 0.7330612540245056

From Second Attept to Third Attepmt there is no significant improvement in model performance i.e. with non benefical categorical variables removed from consideration. Model is optimally trained.

#Summary: 

Max training loss obseved is more 0.55. Neural network model training loss should be close to 0. By adjusting "Ratio of training to test data", "Batch Size" or Fursther "Noise Reduction" may help improve model performance. 


