# Classifying-Fashion-MNIST-1st-Trial

This is one of the exercises in Udacity's Machine Learning Course, which is also my first attempt 
in building a simple Neural Network in PyTorch for classifying the Fashion-MNIST dataset.

In this exercise, 3 hidden layers have been used, with the following architecture: 
          
model = nn.Sequential(nn.Linear(784, 256),
                      nn.ReLU(),
                      nn.Linear(256, 128),
                      nn.ReLU(),
                      nn.Linear(128, 64),
                      nn.ReLU(),
                      nn.Linear(64, 10),
                      nn.LogSoftmax(dim=1))
                      
It looks like even a simple neural network like this can do a great job in classification!

