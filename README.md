# 21Deep-Learning-Challenge

# Analysis 

The goal of this assignment is to create a model that predicts whether applicants funded by Alphabet Soup will be successful. The dataset includes information about over 34,000 organizations that have received funding, with key details such as application type, affiliation, classification, income amount, and the target variable, `"IS_SUCCESSFUL"`, which shows if the funding led to success. The analysis has three main parts:

## PART 1: Data Cleaning
Identification columns like `"EIN"` and `"NAME"` are removed, categorical variables are encoded into numerical values, and the data is split into training and testing sets. The data is also scaled to ensure the model learns effectively.

## PART 2: Neural Network Compilation, Training, and Evaluation

A neural network model is built with input features, hidden layers using `ReLU` activation, and an output layer with a single neuron using `sigmoid` for binary classification. The model is trained using the `"binary_crossentropy"` loss function and the Adam optimizer.

## PART 3: Model Optimization

To improve accuracy beyond 75%, optimizations are applied by adding neurons, layers, changing activation functions, and adjusting the number of training epochs.
After these adjustments, the model is re-evaluated to ensure it can predict success reliably, offering a useful tool for Alphabet Soup to make better funding decisions.


# Results 

After applying various optimizations, the model is re-evaluated using the test data, aiming to achieve an accuracy above 75%. This indicates that the model can reliably predict the success of Alphabet Soup's funding applicants. Adjustments to the network's architecture, training epochs, and data preprocessing help improve the model's accuracy and performance. 
Efforts to improve the model's performance included dropping additional columns, such as `"STATUS"` and `"SPECIAL_CONSIDERATIONS"`, reducing cutoff values for categorical variables, and experimenting with different numbers of neurons and activation functions. However, despite these adjustments, the model's accuracy remained at 72%, which fell short of the 75% target.

# References

- Xpert Learning Assistant
- AskBCS Learning Assistant
- Curriculum content
- Tutoring