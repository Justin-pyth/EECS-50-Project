# EECS-50-Project: Energy Spectral Density Estimation Project
[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Justin-pyth/EECS-50-Project)

Try out our code for yourself using the link above!

# Project Problem and Results
For our project we chose to analyse a finite sinusoidal signal at 100 Hz with random noise. In real world application the results are much more applicable to broadband signals with denser frequencies, and a much longer signal. Since our signal is short, one second long, we do not need to perform averaging over the length of the samples. 
We know that the energy spectrum is the FFT squared which we divide by N to get the ESD.
Once we perform ESD, we create a threshold 10% from the max energy which is a peak at our 100 Hz signal. After denoising this from the FFT of the signal, and zeroing it, we perform IFFT to get the original signal. This filtered signal will have effectively removed the noise for all components for a certain energy threshold thus removing noise from our original frequency.  

Our results outputed a filtered signal cosine signal at the 100 Hz, using the methodology of ESD estimation. 

# References  
[1] Signals, Systems, and Transforms Fifth Edition Authors: Charles L. Phillips | John M. Parr | Eve A. Riskin  
Very helpful [course video series]((https://youtube.com/playlist?list=PLe9mXJw-r7Gx0AZjOIFMLjufRIOI9GgLd&si=i6ijdiXtPpnxBrJt)) by Idaho State Uni  
Matlab video for [PSD estimation and Power Spectrum]((https://www.youtube.com/watch?v=pfjiwxhqd1M))  

