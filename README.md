# A rather simple Deep Convolutional GAN

A small notebook showcasing the development of a small and simple Deep Convolutational GAN using convolutaional layers in the generator and discriminator (DCGAN). It is based off the [original paper, here](https://arxiv.org/pdf/1511.06434.pdf). The DCGAN is trained on the [Street View House Numbers](http://ufldl.stanford.edu/housenumbers/) (SVHN) dataset. These are color images of house numbers collected from Google street view. These convolutional layers also make use of batch normalization to converge and train faster.

If there are some changes or any ML blasphemies that I committed here and there, feel free to open an issue and point me to the right direction! I'm just learning after all! :smile:

## Example output
The output of this model should produce rather realistic images like the ones that it was trained on. Perhaps more epochs could make a difference to yield more interesting and realistic results but it suffices as a proof of concept. 

![output example](images/SVHN_examples.png)

## License
[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

