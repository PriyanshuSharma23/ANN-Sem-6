# Learning Rules

Set of instructions or a mathematical formula which keeps a renforcing pattern in the network.

## 1. Hebbian Learning Rule

- Unsupervised learning rule

- Adjust the weight between two neurons in proportion to the product of their activation.

- Decrease the weight between two nodes if they are working in the opposite direction and vice versa. If there is no correlation between the signals of the two nodes then leave the weights as it is.

- Weight is positive when both the nodes are either positive or negative. else the weight carries a negative sign.

delta W = alpha \* Xi \* y

## 2. Perceptron Learning Rule

- This is an error correction rule used in single layer feed forward models.

- Supervised learning rule

- Rule works by finding the difference between the actual and expected outputs and use that to update the weights. It requires a set of input vectors and weight to produce output

delta W = W + n*(y - y')*x

## 3. Delta Learning Rule

- Depends on supervised learning and has a continuous activation function.

- Least mean square method, minimise error overall training patterns !VERY IMP

- It is based on the gradient descent algorithm. !VERY IMP

- It states that the change in weight is equal to the product of error and the input

## 4. Correlation Learning Rule

It is very similar to Hebbian learning rule the key difference being that it is for supervised learning. The targetted response is used in calculating the weight updates.

delta W = alpha \* xi \* yi

## Competitive Learning Rule

- Winning neuron: the neuron with the maximum net input.

- The output of the winning neuron is set to 1 while others are set to 0.
