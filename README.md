**Hidden-Markov-Model**

Purpose of this repository is to showcase the idea, mathematics and implementation of HMM. I have used R to show the implementation.

![alt text](https://github.com/avinashbarnwal/Hidden-Markov-Model/blob/master/HMM.png)

[source](https://www.wikiwand.com/en/Hidden_Markov_model)

**Problem Formulation**

The number of hidden states is unknown. K is the total number hidden states. We assume that given the hidden states 
![equation](http://latex.codecogs.com/gif.latex?Z_i) , ![equation](http://latex.codecogs.com/gif.latex?P%28Y_i%7CZ_i%29%20%5Csim%20N%28%5Cmu_%7BZ_i%7D%2C%5Csigma%5E2_%7BZ_i%7D%29). Assume the input vector ![equation](http://latex.codecogs.com/gif.latex?%28Y_1%2CY_2%2C...%2CY_n%29), goal is to estimate ![equation](http://latex.codecogs.com/gif.latex?%28Z_1%2CZ_2%2C...%2CZ_n%29), where ![equation](http://latex.codecogs.com/gif.latex?Z_i) can take values from 1,2,...,K. 

Generally for state-space modeling with unknown hidden states. Lets K = 2,3,4 or more. We are suppose to estimate suitable K.
Paramters to estimate transition matrix KxK , ![equation](http://latex.codecogs.com/gif.latex?%5Cmu_%7BZ_i%7D)

Steps:-







