This notebook can be used to estimate the distortion of pulses caused by low and high pass filtering. Basically it just converts the signal to fourier space and cuts off the part of the signal that is outside of the bandwidth:

![alt text](examples\ex_fft.png "Title")

In this example (5MHz-50MHz bw) the pulse gets heavily distorted, both because of the high pass and the low pass:

![alt text](examples\ex_5MHz_50MHz.png "Title")