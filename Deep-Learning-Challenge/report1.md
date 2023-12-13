# Results

### Data Preprocessing

- The target of the model is the "IS_SUCCESSFUL" column. 
- The features of the model are the "NAME", "APPLICATION", "TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", INCOME_AMT,"SPECIAL_CONSIDERATIONS", "STATUS", and "ASK_AMT" columns. 
- The variable removed from the input data is the "EIN" column. 

### Compiling, Training, and Evaluating the Model
The refined model architecture featured two hidden layers, with a notable enhancement in the number of neurons within the first layer—from 80 to 100. This adjustment aimed at boosting overall accuracy. Both hidden layers employed the 'relu' activation function consistently throughout the neural network. The training process remained standardized with a fixed number of epochs set at 100, contributing to the model's convergence.

Significantly, the model achieved the desired performance level, meeting the specified target criteria.

In a further refinement, the "NAME" column was transformed into individual data points, providing an additional layer of granularity to the input data and potentially contributing to the model's improved understanding and performance. 

# Summary
In short, the model achieved an accuracy of 79.18% on the test data and a loss of 0.4777. Consideration for the Random Forest model should be taken, due to this model being ideal for classification problems. 