fill #TO DOES

2nd Exercise:
The Basic Idea
To automate the solving of MNIST-CAPTCHAs, we need to train a neural network that can decode the math problem from the MNIST digits.

The first step is to train a neural network that can recognize the digits one by one.

The next step is to extract the digits from the CAPTCHA problem, use our trained neural network, and then calculate the answer once we have identified the correct numbers.

Simple Neural Network
As a minimal starting point, we define a model with a single linear layer nn.Linear(28*28, 10) that flattens the pixels and produces logits for the 10 classes of MNIST.

