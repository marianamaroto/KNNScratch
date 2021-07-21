# KNNScratch
With scikit-learn library, there is hardly any reason to code a machine learning model from scratch. Except for three reasons 1) You want to really understand how the model works 2) You love coding 3) Your professor makes you. Mine was mainly the third reason but honestly I had a lot of fun coding this all-time ML model. 

Using the famous white wine quality dataset, this code implements the KNN model from scratch, along with AUC and ROC curves to evaluate model. 

The dataset contains 4,898 instances each 
corresponding to a specific white wine, and 12 attributes (fixed acidity, volatile acidity, citric 
acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, Ph, sulphates, 
alcohol, and quality). The variable quality which is a score between 3 and 9 based on sensory 
data was used to create the target variable. Wines with quality of less than or equal to 5 were 
classified as poor (0) and wines with quality of more than 5 were qualified as good wines (1). 
This binary quality attribute was used as the target variable.

https://archive.ics.uci.edu/ml/datasets/wine+quality
