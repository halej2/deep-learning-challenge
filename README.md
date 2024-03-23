# deep-learning-challenge
Data Preprocessing
- In this analysis we are trying to predict whether venture applicants will be successful if funded by Alphabet Soup. As such, our target variable in this analysis is "IS_SUCCESSFUL".
- The features used to predict whether an applicant will be successful are application type, affiliation, classification, use case, organization, status, income amount, special considerations and ask amount.
- Variables that need to be removed that are not targets and variables are the EID and Name of the applicant
  
Compiling, Training, and Evaluating the Model
- For my final model I decided to use 2 layers the first layer had 5 neurons and the second layer had 3 layers. My activation function I used was the sigmoid function. I use these options for my neural network because this is what gave me the best accuracy for my optimazatiton attempt models. I tried more layers and more neurons, but I think this added more "noise" to the model I think the less layers the better.
- I, unfortunately, was not able to achieve the target model performance of 75% accuracy. I wasble to achieve about 73%.
- As an attempt to optimize the model, I decided to try three layers, I tried one layer, and I also tried using more and less Epochs. In addition, I tried different variations of neurons per each layer. I chose to keep all the features as I thought these were all important characteristics in deciding if an applicant would be successful, but if I had to keep optimizing I would try using less features next.
  
Summary: Overall, the neural network may not be the best model for this classification model. I think the neural network has too much "noise", meaning it's finding connections between the data that aren't actually there. I think using a classification model such as random forests which uses decision trees or even KNN (k-nearest neighbor) might be better. A random forest performs feature selection and will decide what features are actually important. If I were given a recommendation to a stakeholder I would suggest they try to make the problem simpler. For example, if I had to keep optimizing this model I would use less features. I would try to predict success rate on features such as amount asked for, income amount and use case. More features may add more "noise" to the model making it harder to make clear predictions for a relatively simple problem.

Referemce:
- I used Week 21 assisngments and office hours with Professor Booth to complete this assignment.
