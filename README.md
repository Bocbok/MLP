# MLP
Multi Layer Perceptron

# Architecture used

For the iris learning problem the best architecture encountered is a 4/4/3 neural network with a learning rate of 0.05.

![](https://i.imgur.com/HbtFMqL.png)

With this architecture we achieve an error of less than 0.05 in 2000 epochs on the train set.

![](https://i.imgur.com/gYbG8pc.png)

We achieve a mean error less than 0.02 on the test set.

![](https://i.imgur.com/6gBmCcf.png)

# 5 hidden layers of 10 neurons

![](https://i.imgur.com/6L2fzEw.png)

![](https://i.imgur.com/Xt4Zkda.png)

With such a lot of layers and neurons the gradient descent method used in the backpropagation algorithm make the error to oscillate between epochs ~100 - ~600 but we end up with an error similar as the one we got with the first architecture.