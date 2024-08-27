# mortality-rate-modelling
Baseline model and two deep-learning models comparing mortality rates in the Ile-De-France region of France.

The baseline model predicts that mortality rates for each age group remain constant year-on-year. The two deep-learning models were an recurrent neural network using a Simple RNN layer and a convolutional neural network.

The training dataset consisted of the years 1921 to 2000, the validation dataset from the years 2001 to 2010 and the test dataset from the years 2011 to 2020.

The lowest achieved error rates of these models was approximately 13% on the test dataset using a convolutional neural network. This error rate thus represents
