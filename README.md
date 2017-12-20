# Spikefinder submission with supervised DeepSpike

This is the code used to create the DeepSpike submission for the spikefinder challenge: http://spikefinder.codeneuro.org/

We train recurrent neural networks trained on the available annotated data. 
For details check [Community-based benchmarking improves spike inference from two-photon calcium imaging data](https://www.biorxiv.org/content/early/2017/08/18/177956)

To see how such networks can be trained in an unsupervised way see [Fast amortized inference of neural activity from calcium imaging data with variational autoencoders](https://arxiv.org/abs/1711.01846)

This algorithm uses the Theano and Lasagne deep learning libraries and is organized as follows:

  * The DataPrep notebook shows how we preprocessed the raw challenge data.
  * The Example_run notebook shows how to train a network on the first challenge dataset and plots some results.
  * The SpikefinderSubmission notebook recreates our challenge submission (outcomment the respective parameter setting to train on each of the 5 datasets)

