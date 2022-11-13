Deep_Learning_Classification_Model

The attached model is able to predict the flower type based on given feature parameters, such as petal length, petal width, sepal length, and sepal width. 
The model was trained using popular iris dataset. 

The model was built on using the concept of deep neural network and keras library. 

The given fratures were sepal length, sepal width, petal length, and petal width; target variable was three different flower type, which are setosa, virginica, and versicolor. 

To impelement the model, a sequential model was built. The epoch and batch_size hyperparameters were tuned. 20% training data was used for validation training set, since the 
total data points were 150 only. 

The epoch vs accuracy plot shows the accuracy level increased with increasing number of epoch. 

FInally, the model was tested using some example feature values, which was correctly classified as 'virginica'.
