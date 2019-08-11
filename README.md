# Text Generation with Recurrent Neural Networks

### Neural Networks Vs Recurrent Neural Network (RNN)

The basic difference between an ANN (artificial neural network) and RNN is that ANN are traditional neural networks, that only transmit data in a sequencial manner. The Data can only move forward to the next layer in the Network but not backwards. In other words these are feed-foward networks, and they cannot form a loop. 

In a Recurrent Neural Network a perceptron can pass it's output to itself, and hence a Loop is formed. They process the input from one or multiple channels, and generate output that would be passed to to theirselves as input again. 

Another key point in understanding the RNN is that the output generated from a perceptron in RNN, is a memory cell, which helps preserve the state of the perceptron, hence forming LSTM - Long Short Term Memory. 

##### Another Example

We've done the classification of Iris Dataset using the ANN, where we trained our model, comprising of two layers of Neurons for processing (feed-forward), and additional one layer for giving output as final result. 
Important thing to note here is that, each layer in the network remembers the input and forgets it once it has processed and passed it to the next layer in line. Once the processed output has gone to the next perceptron the previous perceptron will forget it. 

This will help the ANN to predict the classification of a newly found unclassified Iris flower, by feeding it's features to a trained model but it will not predict that 

Here's the code with full description, how we can use RNN to generate text given a text file
[Source File](rnn_example.ipynb)
