# Handwritten-Text-Recognition

This project implements a Handwritten Text Recognition (HTR) system using deep learning techniques with TensorFlow. The system uses Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), and Connectionist Temporal Classification (CTC) to recognize text from images of handwritten documents.

## Project Structure

### Files and Directories

- **model.py**: Defines the TensorFlow model architecture including CNN, RNN, and CTC components.
- **Dataloader.py**: Loads and preprocesses data from the IAM Handwriting Database.
- **SamplePreprocessor.py**: Contains functions for preprocessing images.
- **analyze.py**: Implements pixel relevance and translation invariance analyses based on the trained model.
- **main.py**: Entry point for running analyses and displaying results.
- **requirements.txt**: Lists dependencies required to run the project.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- NumPy
- OpenCV
- Matplotlib

Install dependencies using:

pip install -r requirements.txt


### Installation

1. Download the project zip file and unzip it.
2. Place the code in your desired directory, e.g., `/content/drive`.
3. Open the Colab notebook `Handwritten_Text_Recognition.ipynb` and execute the cells to run the project.

## Usage

Run the main script to train the model or perform inference:

The project uses the IAM Handwriting Database for training and testing. Ensure the dataset is downloaded and structured as expected by `Dataloader.py`.

### Example Output

Validation character error rate of saved model: 10.624916%
Init with stored values from ../model/snapshot-38
Recognized: "little"
Probability: 0.96625507

Recognized: "MR."
Probability: 0.57650965
