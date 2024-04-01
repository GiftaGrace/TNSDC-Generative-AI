# TNSDC-Generative-AI
Handwritten Digit Conversion GAN

This project aims to convert handwritten images of digits into clear, standardized digital format using a Generative Adversarial Network (GAN).

Getting Started

Prerequisites

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- (optional) Jupyter Notebook for running the provided notebooks

Installation

1. Clone the repository:
   sh
   git clone https://github.com/yourusername/handwritten-digit-conversion-gan.git
   

2. Install the required dependencies:
   sh
   pip install -r requirements.txt
   

Usage

1. Train the GAN model:
   sh
   python train.py
   

2. Convert handwritten images to digital format:
   sh
   python convert.py path_to_input_image.jpg
   

Notebooks

- data_exploration.ipynb: Explore the dataset and visualize handwritten images.
- model_training.ipynb: Train the GAN model and visualize the training process.
- image_conversion.ipynb: Use the trained model to convert handwritten images to digital format.

Dataset

The model is trained on the MNIST dataset, which consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9).

Model Architecture

The GAN architecture consists of a generator and a discriminator. The generator generates synthetic images of digits, while the discriminator tries to distinguish between real and fake images.

Results

The trained model achieves an accurate results on the test set and can convert handwritten images to digital format with high fidelity.

Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request.
