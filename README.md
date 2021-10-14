# UTKFace_NeuralNetwork
Data: https://susanqq.github.io/UTKFace/
### Part A
We implement Multi-layer Neural Network from scratch in order to use it as linear regression to predict age of each face.
The inpute is normalized and its dimention is reduced to 128 features using PCA.
Last layer loss is L2 and other layers have LeakyReLU activation function.
The network learns using SGD with momentum of 0.9 .
We compare loss per trial for:
  # zero weight initialization
  # Xavier weight initialization
  # -0.1 to 0.1 random weight initialization.
  # He weight initialization
  # STep decay learning rate adaption
### Part B
We change the last layer of Part A to classify nationality of each face. We use Negative Log Likelihood loss function.
### Part C
We use Logistic Loss function to use Part A as logistic regression to predict the gender of each face.
