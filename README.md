# information-theory

This was my original code for I232E Information theory April 2021 - June 2021
Class was taught by Brian Kurkoski and Lei Liu at Japan Advanced Institute of Science and Technology

## HW 9

### InfTheory_HW9Revised.ipynb

Codes for calculating capacity of specified channels (BPSK, 4PAM, 8PAM, Gaussian) for given SNR (Signal-to-Noise Ratio)
while interrupted by Gaussian white noise

Implementation uses numerical integration by trapezoidal methods combined with normal summation
because BPSK, 4PAM, and 8PAM are discrete channels

### InfTheory_HW9_2_gradDescent.ipynb

Codes for calculating optimal symmetric channel for given SNR (Signal-to-Noise Ratio)

Implementation uses numerical integration by trapezoidal methods combined with normal summation
and uses gradient descent (or ascent) optimization methods using numerical differentiation
(to be honest, it is not the best possible optimization method since it is slow, sensitive to initial value, and step size)

## HW 13

Codes for implementing Arimoto-Blahut Algorithm in Jupyter-Notebook
Iterating Lagrange multipliers method until self-consistency is achieved

https://www.wikiwand.com/en/Blahut%E2%80%93Arimoto_algorithm

### InfTheory_HW13.ipynb

is the first part for finding capacity of given channel

### InfTheory_HW13_2.ipynb

is the second part for finding Rate-distortion function of given input distribution
