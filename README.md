# Adaline
### Overview
    - Stands for “Adaptive Linear Neuron”.
    
    - The Adaline deviates from Perceptron because there is no cost function in Perceptron and without a cost function Perceptron is minimizing nothing. 

    - The cost function in the Adaline Algorithm is mean square error.
    
    - To minimize cost function, gradient descent is needed.
    
    - The gradient decent should work with differentiable function (has derivative) as the weight update is on the slope’s opposite direction

### GUI
    - User Input:
        - Select two features
        - Select two classes (C1 & C2 or C1 & C3 or C2 & C3)
        - Enter learning rate (eta)
        - Enter number of epochs (m)
        - Enter MSE threshold (mse_threshold)
        - Add bias or not (Checkbox)

    - Initialization:
        - Number of features = 2.
        - Number of classes = 2.
        - Weights + Bias = small random numbers

    - Classification:
        - Sample (single sample to be classified).

### Description
    - Implement the Adaline learning algorithm using MSE
    
    - Single layer neural networks which can be able to classify a stream of input data to one of a set of predefined classes.

    - Use the penguins data in both your training and testing processes. (Each class has 50 samples: train NN with 30 non-repeated samples randomly selected, and test it with the remaining 20 samples)

    - After training
        - Draw a line that can discriminate between the two learned classes.

        - Test the classifier with the remaining 20 samples of each selected classes and find confusion matrix and compute overall accuracy.

        







