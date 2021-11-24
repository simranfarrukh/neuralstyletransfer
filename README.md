# Neural Style Transfer version 1.0

Neural style transfer is an optimization technique used to take two images—a content image and a style reference image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```terminal
pip install matplotlib
pip install Pillow
pip install torch
pip install torchvision
```

## Concept

```python
#  Define two distances: Dc for content and Ds for style.
#  Dc measures how different the content is between two images.
#  Ds measures the style difference between two images.
#  Then create a third image and transform it to minimize the Dc with the content image (content.jpg) and the Ds with style image (monetclaude.jpg)
```

## General Steps

```python
# Import packages and select a device
# Load the images
# Loss functions:
#     Content loss
#     Style loss
# Import a pre-trained model
# Gradient descent
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
