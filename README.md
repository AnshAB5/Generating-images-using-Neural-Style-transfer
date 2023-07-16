# Neural Style Transfer using Pretrained VGG Model

This repository provides an implementation of neural style transfer using a pretrained VGG model. Neural style transfer is a technique that combines the content of one image with the style of another image to generate a new image. In this implementation, we leverage the power of convolutional neural networks, specifically the VGG model, to perform style transfer.

## Prerequisites

To run the code in this repository, you need the following dependencies:

- Python 3.x
- PyTorch
- torchvision
- NumPy
- Matplotlib
- Pillow

## Configuration

You can modify various parameters in the `neural_style_transfer.py` script to control the style transfer process. These parameters include:

- `--content_weight`: Weight for the content loss (default: 1.0)
- `--style_weight`: Weight for the style loss (default: 1000000.0)
- `--num_steps`: Number of optimization steps (default: 200)
- `--save_steps`: Frequency of saving intermediate images (default: 50)
- `--content_layers`: VGG layers used for content representation (default: ['conv4_2'])
- `--style_layers`: VGG layers used for style representation (default: ['conv1_1', 'conv2_1', 'conv3_1', 'conv4_1', 'conv5_1'])

## Acknowledgments

This implementation is based on the neural style transfer technique introduced by Gatys et al. in the paper "A Neural Algorithm of Artistic Style." The VGG model used in this implementation is pretrained on the ImageNet dataset and provided by the torchvision library.

Please refer to the code files and documentation for detailed usage instructions and further explanations.

Enjoy exploring the fascinating world of neural style transfer using the pretrained VGG model!
