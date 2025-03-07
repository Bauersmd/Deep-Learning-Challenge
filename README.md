# Deep-Learning-Challenge
Module 21 Challenge

In this challenge we are given a CSV file from Alphabet Soup non-profit foundation. This CSV file contains over 34,000 organizations that recieved funding from Alphabet over the years. Alphabet Soup is a in the previous sentence a non-profit foundation. They want tools that help select applicants for funding based on the best chances for success in their ventures. 

In the CSV file contains a number of columns that capture metadata about each organization such as:
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

Given the columns above I narrowed it down by removing 2 columns called EIN and NAME

After typing my code and running my first file for Alphabet Soup Charity Optimization my accuracy that I achieved was 72%. From there I created another file and tried to get a higher accuracy than 72%

In my next file for coding I removed more columns to change things up and hope to get a better accuracy. The columns I removed other than EIN and NAME are: 'STATUS', 'SPECIAL_CONSIDERATIONS', 'ORGANIZATION'. The reason I chose these columns is because I felt that removing these columns would help me get a higher accuracy.

From there I added another node hidden layer to change my accuracy that could be higher.

After running my next three codes for a higher accuracy I was unable to change it.

Results: 
Data Preprocessing: 
Bullet 1: What variable(s) are the target(s) for your model?
Answer: IS_SUCCESSFUL column is the target variable from the csv.

Bullet 2: What variable(s) are the features for your model?
Answer: The variables that are features in the data frame are every column after dropping IS_SUCCESSFUL from the dataset.

Bullet 3: What variable(s) should be removed from the input data because they are neither targets nor features?
Answer: The variables that are removed are columns EIN and NAME because they did not have data that benefited the data sets.

Compiling, Training, and Evaluating the Model
Bullet 1:How many neurons, layers, and activation functions did you select for your neural network model, and why?
Answer: In my first attempt I chose numbers 75 and 25 in my nodes_hidden_layers. These nuumbers were randomly chosen from 1-100.

Bullet 2:Were you able to achieve the target model performance?
Answer: Unfortunately I was unable to achieve the model accuracy target of 75%. I was only able to get 72% accuracy.

Bullet 3: What steps did you take in your attempts to increase model performance?
Answer: I added more layers in my In my second and third attempts with random numbers from 1-100. I also switched up my activation functions when trying to achieve the 75% target accuracy.

Summary: 
Looking back at the data and code I can see that I can no longer get a higher accuracy than 72%. The possible chance of getting a higher accuracy would be to do more of a cleanup of the data again which should lead to a higher accuracy. After that you would then try to use the model from the code and try different activations to then find a possible chance of a higher accuracy.
