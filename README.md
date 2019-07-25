# Text Generation with Neural Networks

### Neural Networks Vs Recurrent Neural Network (RNN)

A Conceptual between an ANN (artificial neural network) and RNN is that ANN are traditional neural networks which only transmit data in a sequencial manner. The Data can only be forwarded to the next layer in the Network but not backwards. In other words these are feed-foward networks, and they cannot form a loop. 

The Recurrent Neural Network can pass their output to theirselves, and hence Loop is formed. The process the input from one or multiple channels, and generate output that would be passed to itself. 

##### Real Life Example

We've done the classification of Iris Dataset using the ANN, where we trained our model, comprising of two layers of Neurons for processing (feed-forward), and additional one layer for giving output as final result. 
Important thing to note here is that, each layer in the network remembers the input and forgets it once it has processed and passed it to the next layer in line. Once the processed output has gone to the next perceptron the previous perceptron will forget it. 

This will help the ANN to predict the classification of a newly found unclassified Iris flower, by feeding it's features to a trained model but it will not predict that 
