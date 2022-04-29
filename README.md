# Neural_Network_Charity_Analysis
With my knowledge of machine learning and neural networks, I use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
## Deliverable 1: Preprocessing Data for a Neural Network Model
Using my knowledge of Pandas and the Scikit-Learn’s StandardScaler(), I preprocess the dataset in order to compile, train, and evaluate the neural network model.
- The EIN and NAME columns have been dropped
![image](https://user-images.githubusercontent.com/96395120/165874857-17e08202-dc2f-4222-a663-5af22862d689.png)
- The columns with more than 10 unique values have been grouped together
![image](https://user-images.githubusercontent.com/96395120/165875419-b12a15d7-e19f-4895-851f-25b71e0ff3f8.png)
- The categorical variables have been encoded using one-hot encoding
![image](https://user-images.githubusercontent.com/96395120/165875511-a05de955-764a-45b2-bb18-af164d6f19b5.png)
- The preprocessed data is split into features and target arrays
- The preprocessed data is split into training and testing datasets
![image](https://user-images.githubusercontent.com/96395120/165875606-0309cd74-a1b2-46ea-a580-2a541bf7d39c.png)
- The numerical values have been standardized using the StandardScaler() module
![image](https://user-images.githubusercontent.com/96395120/165875670-d8c0347e-eb69-4128-83fc-232f2387fae2.png)
## Deliverable 2: Compile, Train, and Evaluate the Model
Using my knowledge of TensorFlow, I design a neural network/deep learning model, to create a binary classification model that can predict if an organization will be successful based on the features in the dataset. I thought about how many inputs there are before determining the number of neurons and layers in your model. Once completed I compiled, trained, and evaluated the binary classification model to calculate the model’s loss and accuracy.
- The number of layers, the number of neurons per layer, and activation function are defined
- An output layer with an activation function is created
![image](https://user-images.githubusercontent.com/96395120/165875893-0f67cb8d-ce00-4ca9-a91e-24e110b9e364.png)
- There is an output for the structure of the model
![image](https://user-images.githubusercontent.com/96395120/165876235-8b458e8a-62cc-49ed-89e6-0dde77bf79e0.png)
- There is an output of the model’s loss and accuracy
- The model's weights are saved every 5 epochs
![image](https://user-images.githubusercontent.com/96395120/165876290-c41f6e06-bf66-4833-aeb5-b5907fb3e9d7.png)
- The results are saved to an HDF5 file
![image](https://user-images.githubusercontent.com/96395120/165876483-27bbbacc-deee-4185-a306-f492a7edc2d8.png)
## Deliverable 3: Optimize the Model
Using my knowledge of TensorFlow, I optimized the model in order to achieve a target predictive accuracy higher than 75%. 
- Noisy variables are removed from features
- Additional neurons are added to hidden layers
- Additional hidden layers are added
- The activation function of hidden layers or output layers is changed for optimization
- The model's weights are saved every 5 epochs
- The results are saved to an HDF5 file
## Deliverable 4: A Written Report on the Neural Network Model
#### Overview of the analysis: 
Explain the purpose of this analysis.
 - The purpose of this analysis is well defined
#### Results
There is a bulleted list that answers all six questions
- What variable(s) are considered the target(s) for your model?
- What variable(s) are considered to be the features for your model?
- What variable(s) are neither targets nor features, and should be removed from the input data?
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?
#### Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
- There is a summary of the results
- There is a recommendation on using a different model to solve the classification problem, and justification
- Links to images are working, and code is formatted and displayed correctly
