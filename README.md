# Safety Prediction CNN

A Renku project to demo a pre-trained neural network able to assess which image of a couple is taken in the safer place.
This network has been developed for the Streetwise project using a Siamese network with two VGG19 branches followed by a concatenation of those networks' outputs. A convolutional block, composed of 2 convolutional layers and a maxpooling layer, and a fully-connected layer conclude the network infrastructure, allowing to predict the probability that the images provided as inputs of either of the siamese branches is taken in the place that is perceived as safer.

## Executing the demo

* In Renku, connect to the active environment
* Open the notebook notebooks/demo.ipynb
* Run the notebook to see the results
* You can also play around and change the inputs to the network (the "imgXX.jpg" files), to see the results of the network on different data