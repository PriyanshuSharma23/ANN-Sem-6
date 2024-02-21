# Activation Function

An activation function is used in neural networks to add non linearity in the network. The weighted sum of all the inputs and bias is passed through an activation function.
Activation function makes back propagation possible as they introduce gradient along with the error. (which helps in translating the proportion of error in each node)

## Types of Activation functions

### Linear function

eqn: y = x
**issues**

- Do not introduce any non linearity
- Output of all the layers will be the linear combination of the layers

### Sigmoid function

- 'S' shaped graph
- Equation = 1 / (1 + e^-x)
- Usually used in output layer for binary classification.

### Tanh

- equation: 2 / (1 + e ^ (-2x)) - 1
- value range: -1 to 1
- nature: non linear
- Usually used in hidden layers as it ranges from -1 to 1, it brings the mean of the hidden layers closer to 0. Hence it helps centering the data by bringing mean closer to 0. Makes learning much easier in the next layer.

### Relu

- Rectified linear unit, most widely used
- equation: A(x) = max(0, x)

- value range: [0, inf)

- Much faster than sigmoid and tanh as it uses simple calculations.

### Softmax

- nature: non linear
- Used for multiclass identification problems. It squeezes the outputs of each node between 0 and 1 and divided them by the sum of outputs.

- The output of softmax activation function helps us to determine the probabilities of different outcomes.
