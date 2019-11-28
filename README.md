
![image](https://miro.medium.com/max/1400/1*0sxXMXi1IN6ba3VOrLIBoQ.png)
_[Image Source](https://medium.com/machine-learning-bites/deeplearning-series-sequence-models-7855babeb586)_

# Sequence Models
Repository contains examples of sequence deep learning models used in small projects

## Introduction
When I first found out about [sequence models](https://medium.com/machine-learning-bites/deeplearning-series-sequence-models-7855babeb586), I was amazed with how easily they can be applied to a wide range of problems: text classification, text generation, music generation, machine translation and others.
I got several ideas of how to have fun with sequence models, that's why I created this repository for storing Kaggle kernels and scripts with implementations.

## 1. Kernel Title Generation for Kaggle
I got an idea to use [Meta Kaggle dataset](https://www.kaggle.com/kaggle/meta-kaggle) to train a model for generation of new kernel titles. This could help to capture some trends for Kaggle kernels and give an inspiration. In [this kernel](https://www.kaggle.com/aleksandradeis/lstm-for-kernel-title-generation-with-pytorch):

* I loaded and preprocessed Kaggle data on kernels.
* Implemented and trained a sequence model with LSTM for generation of new Kaggle titles.

[Link to the notebook](https://github.com/Lexie88rus/sequence-models/blob/master/lstm-for-kernel-title-generation-with-pytorch.ipynb).

## References and Further Reading
1. [The Unreasonable Effectiveness of Recurrent Neural Networks](https://karpathy.github.io/2015/05/21/rnn-effectiveness/)
2. [Long Short-Term Memory: From Zero to Hero with PyTorch](https://blog.floydhub.com/long-short-term-memory-from-zero-to-hero-with-pytorch/)
3. [LSTMs for Time Series in PyTorch](https://www.jessicayung.com/lstms-for-time-series-in-pytorch/)
4. [Sampling from an RNN](https://pytorch-nlp-tutorial-ny2018.readthedocs.io/en/latest/day2/sampling.html)
