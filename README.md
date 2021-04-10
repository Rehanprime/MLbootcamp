# MLbootcamp
## Winter of Code 3.0 ML Bootcamp <br/>
Hello,I am Mohd Rehan.Here I am working on my project for Winter of Code 3.0 ML Division. <br/>
I have implemented following machine learning algorithms as part of my project:

## 1) Linear regression
The main function is **Linear_regression** where the model is trained using input data.It returns the weight after training.
Using the weight matrix and the test data,values can be predicted.

Accuracy:23.99%.

I plotted a graph of cost vs number of iterations to visualise the reducing loss.

## 2) Logistic regression
The main function is **Logistic_regression** where we input the training x,training label,learning rate and number of iterations.
It returns the optimised weight matrix using which we can predict output using test data.
For each test case,it will predict the probability of it belonging to each of the 10 classes.The final predicted output will be the one having 
maximum probability.

Accuracy of the model:87.2%

## 3) KNN
There are two functions:**euclid_distance**-to calculate euclid distance of a test dataset with every training dataset,returning distances.

Second function:**prediction** ,which uses distances from the euclid_distance function and predict the output.

Accuracy:94%

## 4) Neural network
I implemented a three layer neural network containing one input layer,one hidden layer and one output layer.
Two randomly generated theta matrix and training data are provided as input.
After training the model,the optimised theta's are returned.
Using these weights and training data,we feed forward using our test data and calculate our prediction.
