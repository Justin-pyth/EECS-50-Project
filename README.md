# EECS-50-Project
Energy Spectral Density Estimation Project


# Background and motivation.
Energy spectral density (ESD) estimation
Estimates the distribution of the signal's energy over frequency domain. ESD can give the various components of the frequency of the signal and relative strengths. Used to help eliminate random components of noisy signal, and amplifying the legitimate components from signal's frequency spectrum
Involves autocorrelation - correlating signal with itself
Can interpret ESD as the energy per unit bandwidth, affected by the frequency components of the signal. Additionally, the total area under the ESD function will give the total signal energy.
Note that ESD is when a signal is concentrated at a finite time interval or when total energy is finite. This differs from power spectral density or PSD which applies over all time or an "infinite" time interval.


# Equations:
Parseval's Theorem

Parseval's relates the energy within the time domain to the frequency domain. 

Sample estimate of the autocorrelation:


# Problem definition:
Our proposed experiment is given a noisy signal, and calculate the energy spectrum. Apply a filter to remove frequency components with a certain energy bandwidth. The signal will most likely be continuous and finite. So we will need to take N samples and apply autocorrelation.


# Proposed methods: 
Parseval's theorem will be the summation of FFT in Matlab.
Matlab has tools like FFT and DFT to apply the above mentioned methodology.
Matlab also has a Spectrogram toolbox and specific tools like periodogram and pwelch (Welch's) which are for PSD but can be adapted for ESD.
We have created a github repository and will be using Matlab's livescript docs to document our code and analysis.


# List of people in your group. What are the tasks of each person?
Tara Pai, Katrina Gong, Justin Wu
We will do the following tasks collaboratively: Background and motivation, Sample calculations, Programming, Conclusion and discussion


# References:
Introduction to Digital Communications Book 2016 Author: Ali Grami
Signals, Systems, and Transforms Fifth Edition Authors: Charles L. Phillips | John M. Parr | Eve A. Riskin
Online resources:
Very helpful course video series by Idaho State Uni
Wikipedia Article
StackExchange
Matlab Help

