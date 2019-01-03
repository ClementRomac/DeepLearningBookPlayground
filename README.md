# What is this repository ?

This repository aims to put what I've learned from the [DeepLearning Book](http://www.deeplearningbook.org/) in practice.
I'll implement the NeuralNets with [Tensorflow](https://www.tensorflow.org/).

You can find the conclusion presentation [here](https://github.com/ClementRomac/DeepLearningBookPlayground/Presentation.pdf)

# Summary

## Chapter 6 - 7 - 8 : FeedForward NN and Optimization

In this chapter, I implemented a classic feedforward model and tested a few optmization and regluarization methods. 
I used the [notMNIST dataset](http://yaroslavvb.blogspot.fr/2011/09/notmnist-dataset.html).

## Chapter 9 : Convolutional Neural Net

In this chapter, I implemented a convolutional neural network on the [notMNIST dataset](http://yaroslavvb.blogspot.fr/2011/09/notmnist-dataset.html). I tried a few architectures and played with plotting the conv weights/layers.

## Chapter 10 : Recurrent Neural Net

For this chapter, I wanted to use RNN in the context of NLP. So I tried to make a (very silmplified) Google Neural Machine Translation with a Seq2Seq based on LSTM cells. I used this [tutorial](https://machinelearningmastery.com/prepare-french-english-dataset-machine-translation/) to get a clean French-to-English dataset and [this one](https://machinelearningmastery.com/develop-neural-machine-translation-system-keras/) to prepare data before entering the Neural Net.