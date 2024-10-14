# Image Colorization with OpenCV

This project uses a pre-trained deep learning model from OpenCV to colorize grayscale images. The model leverages a neural network architecture that transforms grayscale input into colorized output.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Model Files](#model-files)
- [Requirements](#requirements)
- [License](#license)
- [Contributing](#contributing)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>


Install the required packages:

bash

    pip install numpy opencv-python matplotlib

Usage

    Place your grayscale image in the project directory or specify its path in the script.

    Update the image_path variable in the script to point to your grayscale image:

    python

image_path = 'img5.jpg'  # Replace with your image path

Run the script:

bash

    python colorization.py

    The original and colorized images will be displayed using Matplotlib.

Model Files

This project downloads the required model files automatically. The following files are used:

    Prototxt File: Defines the network architecture.
    Caffe Model: Contains the trained weights for the network.
    Cluster Centers: Used for colorization transformations.

These files are downloaded from the OpenCV repository and stored in the model directory.
Requirements

    Python 3.x
    OpenCV
    NumPy
    Matplotlib

    Output

Here are some examples of the output:
Original Image

Colorized Image

Replace path/to/original_image.jpg and path/to/colorized_image.jpg with the actual paths to your images.

License

This project is licensed under the MIT License. See the LICENSE file for more information.
