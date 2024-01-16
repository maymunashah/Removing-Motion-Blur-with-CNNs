# Removing-Motion-Blur-with-CNNs

# MNIST Motion Blur Removal with CNN

## Overview

This repository contains a Jupyter Notebook that demonstrates the process of removing motion blur from images in the MNIST dataset using a Convolutional Neural Network (CNN). The MNIST dataset, originally consisting of handwritten digits, is a popular resource for training and testing image processing systems. In this project, we introduce a synthetic motion blur to these images and then employ a CNN to effectively remove this blur, thereby restoring the images to their original, unblurred state.

## Project Description

The MNIST dataset is a cornerstone in the field of machine learning, particularly for those venturing into the realm of image recognition. However, real-world images often come with various imperfections, such as motion blur, which can significantly degrade the performance of machine learning models. Addressing this challenge, our project aims to simulate a common real-world scenario where images are blurred due to motion. We then use a CNN, known for its efficacy in image recognition and processing tasks, to deblur these images.

### Key Features:

- **Synthetic Motion Blur:** We apply a synthetic motion blur to the MNIST dataset images. This process is carefully designed to mimic real-world motion blur.

- **CNN Architecture:** The notebook details the architecture of the Convolutional Neural Network used for deblurring. This includes layers designed specifically for handling the intricacies of blurred images.

- **Training and Evaluation:** We provide a comprehensive guide on training the model, along with the necessary code and explanations. The evaluation section demonstrates the model's performance in deblurring images.

- **Visualization:** The notebook includes visual comparisons between original, blurred, and deblurred images to showcase the effectiveness of our approach.

## Getting Started

### Prerequisites

Before running the notebook, ensure that you have the following installed:
- Python 3.x
- Jupyter Notebook
- TensorFlow 
- Keras
- NumPy
- Matplotlib

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/mnist-motion-blur-removal.git
   ```
2. Navigate to the cloned repository:
   ```
   cd mnist-motion-blur-removal
   ```
3. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

### Running the Notebook

Open the Jupyter Notebook in your preferred environment and run the cells sequentially to observe the process and results of the motion blur removal.

## Contributing

Contributions to this project are welcome. Please feel free to fork the repository, make changes, and submit pull requests. For major changes or questions, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The MNIST dataset creators for providing a fundamental resource for machine learning.
- The TensorFlow team for their comprehensive deep learning library.
- Contributors to the OpenCV project for their powerful image processing tools.

---

**Note:** This project is for educational purposes and is not intended for use in production environments. The effectiveness of the deblurring model may vary based on the characteristics of the motion blur applied to the images.
