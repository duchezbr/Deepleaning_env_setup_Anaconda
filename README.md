# Deepleaning_env_setup_Anaconda
Instructions for setting up an Anaconda environment that can be used for deep learning

## From the Anaconda Prompt

### Create environment named tensorflow
(base) C:\Users\my_name> conda create -n tensorflow pip python=<version of python>

### Activate conda environment
(base) C:\Users\my_name> activate tensorflow

### To install GPU version of TensorFlow
(base) C:\Users\my_name> pip install tensorflow-gpu

### To install CPU version of TensorFlow
(base) C:\Users\my_name> pip install tensorflow

### Test installation
(base) C:\Users\my_name> activate tensorflow
(tensorflow) C:\Users\my_name> python
>>> import tensorflow as tf
>>> hello = tf.constant('Hello, TensorFlow!')
>>> sess = tf.Session()
>>> print(sess.run(hello))

### Install Keras
base) C:\Users\my_name> pip install keras

### Test
activate tensorflow
(tensorflow) C:\Users\my_name> python mnist_mlp.py
