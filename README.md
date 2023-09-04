# Forward-propagation-algorithm-and-code.
# this is a simple neural network for prediction.
Each data point is a customer. 
The first input is how many accounts they have, and the second input is how many children they have.
The model will predict how many transactions the user makes in the next year. 
The input data has been pre-loaded as input_data, and the weights are available in a dictionary called weights.
The array of weights for the first node in the hidden layer are in weights['node_0'], and the array of weights for the second node in the hidden layer are in weights['node_1'].
The weights feeding into the output node are available in weights['output'].
NumPy will be pre-imported as np in all the program.
 •	Calculate the value in node 0 by multiplying input_data by its weights weights['node_0'] and computing their sum. This is the 1st node in the hidden layer.
 •	Calculate the value in node 1 using input_data and weights['node_1']. This is the 2nd node in the hidden layer.
 •	Put the hidden layer values into an array. And print it.
 •	Generate the prediction by multiplying hidden_layer_outputs by weights['output'] and computing their sum.
 •	Then we will print the Ouput layer finaly ( prediction output ).
