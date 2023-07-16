# Number Recognition

This project focuses on handwritten digit recognition using the MNIST dataset and a Neural Network. The goal is to develop a system that can accurately detect and classify scanned images of handwritten digits.

## Dataset

The MNIST dataset is used, which consists of 60,000 training images and 10,000 testing images. Each image is a 28x28 grayscale image representing a handwritten digit from 0 to 9.

## Implementation

The project is implemented using Python and the Keras library.

1. Data Preprocessing: The input images are reshaped into a 1D array and normalized to have pixel values in the range of 0-1. The target labels are one-hot encoded.

2. Neural Network Model: A Sequential model is created with multiple layers, including Dense layers and Dropout layers to prevent overfitting.

3. Model Training: The model is compiled with an appropriate loss function and optimizer. It is then trained on the training dataset with a specified number of epochs and batch size.

4. Model Evaluation: The trained model is evaluated on the testing dataset to measure its accuracy in recognizing handwritten digits.

5. Visualization: The accuracy and loss curves are plotted to visualize the model's performance. Additionally, a subset of input images with their corresponding labels is displayed to provide a visual representation of the dataset.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/number-recognition.git`

2. Install the necessary dependencies: `pip install -r requirements.txt`

3. Run the jupyter notebook.

## Results

The model achieves an accuracy of 98.12% on the testing dataset, showcasing its effectiveness in recognizing handwritten digits.

## Acknowledgements

This project was completed as part of the internship program offered by Bharat Intern. We would like to thank Bharat Intern for providing us with the opportunity to work on this assignment.

