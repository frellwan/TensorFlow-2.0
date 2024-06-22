# TensorFlow 2.0 Course 2 Repository

Welcome to the TensorFlow 2.0 Course 2 repository. This repository contains assignments and tutorials for each week of Course 2, focusing on the keras functional API.
### Key Points
  - Multiple input and output layers
  - Tensors and variables
  - Accessing model layers
  - Freezing layers (to avoid training)
  - Keras datasets
  - Dataset generators
  - Image augmentation
  - The Dataset class and training with Datasets
  - Padding and masking sequence data
  - The Embedding layer
  - The Embedding Projector
  - Recurrent neural network layers
  - Stacked RNNs and the Bidirectional wrapper
  - Model subclassing
  - Custom layers
  - Automatic differentiation
  - Custom training loops
  - tf.function decorator

### Assignments

- **Assignment 1: Transfer Learning**
  - Use a pretrained model (MobileNetV2.h5) to classify cats and dogs. Freeze  

- **Assignment 2: Data Pipeline with Keras and tf.data**
  - implement a data processing pipeline using tools from both Keras and the tf.data module.
  - Use the ImageDataGenerator class in the tf.keras module to feed a network with training and test images from a local directory containing a subset of the LSUN dataset, and train the model both with and without data augmentation.
  - Use the map and filter functions of the Dataset class with the CIFAR-100 dataset to train a network to classify a processed subset of the images.

- **Assignment 3: Language model for the Shakespeare dataset**
  - Use the text preprocessing tools and RNN models to build a character-level language model. 
  - Train the model on the works of Shakespeare, and use the network to generate text.
 

- **Assignment 4: Residual network**
  - Use the model subclassing API together with custom layers to create a residual network architecture.
  - Train the custom model on the Fashion-MNIST dataset by using a custom training loop and implementing the automatic differentiation tools in Tensorflow to calculate the gradients for backpropagation.

- **Assignment 5: Nueral Translation Model**
  - neural network that translates from English to German.
  - Use concepts from throughout this course 2, including building flexible model architectures, freezing layers, data processing pipeline and sequence modelling.
