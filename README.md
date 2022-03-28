# python3.7_neuralNetwork
Tutorials: https://www.techwithtim.net/tutorials/python-neural-networks/

### Text_Classification 
Possible Issues:
1. AttributeError: 'str' object has no attribute 'decode' (while Loading a Keras Saved Model)
    - Solution: downgrading the h5py package (in my case to 2.10.0)
