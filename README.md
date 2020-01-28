# W251-HW04

### Part 2: 

1. Name all the layers in the network, make sure you understand what they do.

* Input layer takes the raw 24x24 grey-scale pixel values
* 1st Convolutional layer with a filter size of 5, 8 filters and padding of 2 with relu activation
* 1st Pooling layer - Downsampling layer
* 2nd Convolutional layer with a filter size of 5, 12 filters and padding of 2 with relu activation
* 2nd Pooling layer - Downsampling layer
* Fully connected layer to compute classification scores into the 10 different digits with softmax

2. Experiment with the number and size of filters in each layer. Does it improve the accuracy?

The more and larger the filter, the better the accuracy, but training is much slower. 

3. Remove the pooling layers. Does it impact the accuracy?

Training is slower, and accuracy is more stable during training. Training accuracy seems somewhat better

4. Add one more conv layer. Does it help with accuracy?

Accuracy seems somewhat worse. 

5. Increase the batch size. What impact does it have?

A larger batch size, gave higher accuracy. 

6. What is the best accuracy you can achieve? Are you over 99%? 99.5%?

It can get erratic as it trains more data, but best was around 98% that I've noticed. 

### Part 3: Attached in repository
