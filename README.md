# GridSearch-Pipelines

The given repository consists of two methods used on the california housing dataset.
The target variable was the 'Median House Price'

A) In the first approach, the pipeline encapsulated the scaler and Ridge regressor by tuning it's hyperparameter
alpha.

Results were: 

Best value for regressor_alpha = 12.9154

Best score for pipe = 0.60

B) In the second approach, the pipeline encapsulated the scaler, and the block which applied GridSearch on the Ridge.

Results:

Best value of alpha = 12.9154

Best score = 0.594
