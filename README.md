# AutoVision
## traffic sign detection and recognition

This project is a Traffic Sign Recognition Tool built using Convolutional Neural Networks (CNN) with Keras for the model, OpenCV for image processing, and Tkinter for the graphical user interface (GUI).

## Features

- Recognizes various traffic signs from images.
- User-friendly GUI for image upload and prediction display.
- Pre-trained model provided for quick setup and usage.

## Tech Stack

- **Programming Language**: Python
- **Libraries and Frameworks**:
  - **Keras**: For building and training the CNN model.
  - **TensorFlow**: Backend for Keras.
  - **OpenCV**: For image processing tasks.
  - **NumPy**: For numerical operations.
  - **scikit-learn**: For additional machine learning utilities.
  - **Matplotlib**: For visualizing data and model performance.
  - **Pillow**: For handling image files.
  - **Tkinter**: For creating the GUI.
- **Dataset**: [German Traffic Sign Recognition Benchmark (GTSRB)](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset)


## Description:
Welcome to the Traffic Sign Classification project! This repository contains the code and resources for a deep learning model that can classify various traffic signs with high accuracy. Whether you're interested in computer vision, machine learning, or road safety, this project offers valuable insights and practical applications.

## Key Features:

Training Script: A Jupyter Notebook that demonstrates the training process of a deep convolutional neural network (CNN) on a traffic sign dataset with 47 different classes.

Model Evaluation: An evaluation of the model's performance, including accuracy metrics and visualizations of results.

Tkinter GUI: A Python script with a Graphical User Interface (GUI) built using Tkinter, allowing users to upload images of traffic signs for instant classification.

## How to Use:

Clone this repository to your local machine.
Navigate to the project directory.
Open and run the Jupyter Notebook to train the traffic sign classification model.
Use the provided Python script to launch the GUI for model testing.
Dataset:
The project uses a traffic sign dataset, which includes various types of traffic signs collected from real-world scenarios.

## Requirements:

Python 3.x
TensorFlow
Keras
Tkinter
scikit-learn
Pillow (PIL)
Contributions:
Contributions to this project are welcome! Whether it's fixing bugs, adding new features, or improving documentation, your contributions help make this project better.

traffic-sign-recognition/
│
├── data/
│ ├── train/ # Training dataset
│ ├── test/ # Test dataset
│ └── ...
│
├── models/
│ ├── model.h5 # Trained Keras model
│ └── ...
│
├── notebooks/
│ ├── data_exploration.ipynb
│ ├── model_training.ipynb
│ └── ...
│
├── src/
│ ├── gui.py # Tkinter GUI implementation
│ ├── image_processing.py # Image preprocessing functions using OpenCV
│ ├── model.py # CNN model definition and training script
│ └── ...
│
├── main.py # Main script to launch the application
├── requirements.txt # List of required Python packages
└── README.md # Project documentation



## Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/traffic-sign-recognition.git
   cd traffic-sign-recognition
Create and activate a virtual environment (optional but recommended):


python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required dependencies:


pip install -r requirements.txt
Download the GTSRB dataset and place it in the data/ directory.

Run the application:


python main.py
How to Use
Launch the application:


python main.py
Upload an image of a traffic sign using the "Upload Image" button in the GUI.

View the predicted class of the traffic sign displayed on the GUI.

Model Training
If you want to train the model from scratch, use the provided Jupyter notebooks in the notebooks/ directory. Ensure the GTSRB dataset is placed correctly and follow the steps in the data_exploration.ipynb and model_training.ipynb.

Dependencies
Ensure you have the following Python packages installed (included in requirements.txt):

tensorflow
keras
opencv-python
numpy
scikit-learn
matplotlib
pillow
tkinter
Install them using:


pip install -r requirements.txt
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
German Traffic Sign Recognition Benchmark (GTSRB) dataset.
Keras and TensorFlow for the deep learning framework.
OpenCV for image processing.
The contributors and maintainers of the libraries and tools used in this project.
