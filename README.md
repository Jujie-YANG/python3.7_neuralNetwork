# python3.7_neuralNetwork
Tutorials: https://www.techwithtim.net/tutorials/python-neural-networks/

### NN.py
- Basic classification: Classify images of clothing
- Tutorial guide: https://www.tensorflow.org/tutorials/keras/classification

### Text_Classification.py
- Text classification with TensorFlow Hub: Movie reviews
- Tutorial guide: https://www.tensorflow.org/tutorials/keras/text_classification_with_hub
- Possible Issues:
   1. AttributeError: 'str' object has no attribute 'decode' (while Loading a Keras Saved Model)
       - Solution: downgrading the h5py package (in my case to 2.10.0)
