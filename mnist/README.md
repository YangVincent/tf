# Source
https://www.tensorflow.org/tutorials/layers

# Resources
* [Neurons/Activation Function](https://ujjwalkarn.me/2016/08/09/quick-intro-neural-networks/ )
* [Multilayered Neural Net Visualization](http://scs.ryerson.ca/~aharley/vis/fc/)
* [Why deep layers?](https://stats.stackexchange.com/questions/182734/what-is-the-difference-between-a-neural-network-and-a-deep-neural-network-and-w?rq=1)
* [Intuitive Convnet](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/)


# Notes

#### Convolutional Neural Networks
* Used for image classification
* Apply filters to raw pixel data to learn higher level features, which
is then used by mdoel for classifications.
* 3 parts:
  1. Convolutional layers: Apply convolution filters. Create single value
  outputs. Uses ReLu activation function to introduce nonlinearities.
    * Introduce nonlinearities why?
    * What is ReLu?
  2. Pooling layers: Downsample image data to reduce dimensionality of feature.
    * Common alg is max pooling, which uses max value for subregions. 
  3. Dense (fully connected) layers perform clasification. Every node in layer is connected to every node in preceeding layer. 
* Softmax activation function: Generates 0-1 for each node, sum of all values = 1. 
How likely image falls into target class.
