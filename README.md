# Moving-Average-Filter-MA-

The moving average filter is a simple Low Pass FIR (Finite Impulse Response) filter commonly used
for smoothing an array of sampled data/signal. It takes M samples of input at a time and takes the
average of those M-samples and produces a single output sample. It is a very simple LPF (Low Pass
Filter) structure that comes handy for scientists and engineers to filter unwanted noisy components
from the intended data.
As the filter length increases, (indicated by the parameter M) the smoothness of the output also
increases, whereas the sharp transitions in the data are made increasingly blunt. This implies that this
filter has excellent time domain response but a poor frequency response.
The MA filter performs three important functions:
1) It takes M input points, computes the average of those M-points and produces a single output point
2) Due to the computation/calculations involved, the filter introduces a definite amount of propagation
delay
3) The filter acts as a Low Pass Filter (with poor frequency domain response and a good time domain
response).
