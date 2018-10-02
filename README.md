# Machine-Learning-Note
## Supervised Learning
Labels y and features x   
For the supervised learning, the dataset has labels   
There are two models in supervised learning, including regression and classification.   
Loss is used to describe the differences between the true value and predicting value. Loss is like KPI, the boss asks the employees(model) to achieve the goal(become the best model), if the loss is too large, the employees(model) must do something to decrease it because the boss penalize them based on the loss. In general, we use L2 loss (= the square of the difference between the label and the prediction)     
How to reduce the loss? Gradient decent.    
We could regard the learning rate as hypeparameters
Mini batch gradient decent.   
There are three assumption in supervised learning:  
1. The samples we drop from the same distribution follow iid(independent identical distribution)    
2. The distribution is stable and will not change.  
3. We always drop train data, test data and validation data from the same distribution.  
