# Exercise 4


This is the assignment for the third exercise. The order in which you should work through the notebooks is as follows:

1. [exercise4_sgd.ipynb](./exercise4_sgd.ipynb):  Just a recap on the gradient descent implementation from the previous exercise, then shows an implementation of SGD using mini-batches. You do not have to do anything in here.  
2. [exercise4_template.ipynb](./exercise4_template.ipynb): : Contains the actual tasks and instructions. Basically, you should implement some other optimizers (SGD with momentum, SGD with nesterov momentum, Adagrad) using the equations from the lecture slides. Copy this notebook and rename it for each optimizer that you implement (e.g. exercise3_sgd_momentum.ipynb, exercise3_sgd_nesterov_momentum.ipynb, exercise3_adagrad.ipynb).
3. [exercise4_optimizers_comparison.ipynb](./exercise4_optimizers_comparison.ipynb): Using this notebook, you can compare how the different optimizers perform on this dataset. The image shown there is how it could look if you implemented all optimizers. Note that this comparison is not a general benchmark of these optimizers. This is a very simple dataset and how good an optimizer works is highly dependent on the dataset, the network architecture and how you set the optimizer parameters (e.g. learning rate). On a real dataset, you will most likely have to try out different optimizers and various optimizer settings to see what works best on the data and network that you work with.


