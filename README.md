# DeepGauge: Multi-Granularity Testing Criteria for Deep Learning Systems

This repository contains the PyTorch implementation of **Top-k Neuron Patterns** testing coverage proposed in [DeepGuage](https://dl.acm.org/doi/10.1145/3238147.3238202) paper. In this [document](https://docs.google.com/document/d/17_p2V4B1Ll59nmzX0dHNBi0lpnndYwCWxyUHhvq5SNg/edit?usp=sharing), I have also summarized the research article as well as described its stengths, weaknesses and possible ways to extend this execullent work.

This repository contains two files:
1.   *DeepGauge.ipynb*: Google Colab file containing the Pytorch implementation. 
2.   *LeNet5.pth*: This file contains the state (weights and bias) of a trained LeNet5 model.

You can either re-train a new LeNet5 model using the initial sections of DeepGauge.ipynb notebook and then compute the top-k Neuron Pattern coverage result on the MNIST test set using the **Top-k Neuron Patterns** section of this notebook. 
*Note: With this approach, there might be minor changes in the coverage results compared to the currently displayed results.*

Otherwise, you can directly use the pre-trained model in the notebook and start from the **Top-k Neuron Patterns** section to rerun and reproduce the results.
