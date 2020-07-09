# Evaluation of Image Colourization Approaches

### Abstract

> This paper delves into the modern ways of adding color to monochrome - black-and-white - images, through the use of deep learning. We take inspiration from previous works to implement a U-Net architecture that attempts to colorize 64x64 images taken from the Imagenet dataset. The network is used to implement two different methods of colorization, one through regression and the other through classification. The training was done on a dataset of 50000 images for the regression, and 30000 for classification. The results indicate successful colorizations using both methods with the U-net architecture. The way of classification shows more vibrant colors than regression, but also assesses bolder colors which can lead to strange results. Improvements to the results could possibly be achieved through a variety of adjustments, such as a larger dataset, a more advanced network as well as training the network training.

## Deep Learning Image Colorization

> This project aimed to replicate the results of previous papers while performing additional evaluations of colorization techniques.

Image Colorization by Deep Neural Networks is a challenging problem that is actively researched. The project included building a Deep Neural Network with associated data pipelines and applying state of the art image colorization techniques and comparing them with more classic deep learning approaches based on regression. Through this, I gained a deeper understanding of the strengths and weaknesses of both. Results aligned with earlier works in the field was found.

<p align="center">
 <img src="./images/colorization.png" />
 <p><i>Colorized Images Using a Deep Learning Neural Network</i></p>
</p>

## Development setup

Python 3.7 with Jupyter Notebook and Tensorflow.

## Meta

> This was a group project done for a course in Deep Learning at KTH.

Erik Båvenstrand – [Portfolio](https://bavenstrand.se) – erik@bavenstrand.se

Distributed under the MIT license. See `LICENSE` for more information.

[github.com/ErikBavenstrand](https://github.com/ErikBavenstrand)
