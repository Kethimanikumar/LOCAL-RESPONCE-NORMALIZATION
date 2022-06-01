In biological brain functionality, there is a concept called lateral inhibition. This refers to the capacity of one stimulated neuron to bring its neighbors under control. The main agenda for us is to have a local peak value for finding the maximum value in the neighborhood. 

This is useful when we are dealing with ReLU neurons. ReLU neurons have unbounded activations, and we need local response normalization (LRN) to normalize them. To do this, we need to identify high frequency features. By applying LRN, the neurons becomes more sensitive than their neighbors. This is used in an ImageNet ConvNet process, as discussed in the paper mentioned previously.

