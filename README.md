# image_classfier

Create your own classes and training data to train a neural network to classify inputted images

## Setup

Once you have downloaded the repository you will need to unzip the [starter network folder](Image-AI%20(V3.5)/startNetworkFolder%20zipped.zip) in the [programs folder](Image-AI%20(V3.5)) and then move the file called startNetwork.JSON out of the unzipped folder and into the [main folder](Image-AI%20(V3.5)/startNetworkFolder%20zipped.zip) so that the program can properly load up the starting weights and biases of the initail untrained network (this improves train time and success for other applications)


## Controls

### Classes

Classes represent different images for the network to classify, for example to classify whether a there is a person in the picture or not you would rename class 1 to person and then use the plus button to take pictures where a human is present and then for class 2 you would rename it to no human and then either upload or photograph pictures without people in and then click the train button to start the training of the network. Once trained you can then see the how successful the network was and try it out in realtime with your camera

### Learning Rate

Learning rate controls the size of the steps taken during gradient descent, for those who are unsure I would reccomend a value of 0.05 to 0.2

### Network Activation Function

The dropdown determines the network activation functions, this can either help or inhibit your network during the training process and if you are unexperienced I would reccomend leaving this value untouched as the default setting of "sigmoid" yields the best results in most cases
