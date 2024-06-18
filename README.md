# PRODIGY_ML_03
Title: Cat-Dog Image Classifier using SVM Description: This repository contains code for building a Support Vector Machine (SVM) model to classify images of cats and dogs from the Kaggle dataset. The SVM model is trained on a labeled dataset of cat and dog images to predict the class of new images as either cat or dog.
PRODIGY_ML_03 - Image Classifier using Support Vector Machine (SVM)
Welcome to PRODIGY_ML_03! This project implements an image classifier using Support Vector Machine (SVM) for the task of classifying images of cats and dogs from the Kaggle dataset.

Project Structure
data/: Contains the dataset of cats and dogs images.
src/: Contains the source code for data preprocessing, model training, and evaluation.
README.md: The main documentation file you're currently reading.
Prerequisites
Python 3
Jupyter Notebook
Required Python libraries: numpy, pandas, matplotlib, scikit-learn, Pillow, tqdm
Getting Started
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/astromanu007/PRODIGY_ML_03.git
Download the Kaggle "Cats and Dogs" dataset from here and extract it into the data/ folder.

Open a terminal and navigate to the project directory:

bash
Copy code
cd PRODIGY_ML_03
Install the required Python libraries if you haven't already:

Copy code
pip install -r requirements.txt
Data Preprocessing
Preprocess the images by resizing them and converting to grayscale.

Load and preprocess the dataset using the Jupyter Notebook provided in the src/ directory.

Training the SVM Model
Split the dataset into training and testing sets.

Initialize and train the SVM classifier using the provided code in the Jupyter Notebook.

Evaluating the Model
Calculate the accuracy of the model on the test set.

Visualize sample predictions to evaluate the model's performance.

Conclusion
This project demonstrates the implementation of an image classifier using Support Vector Machine (SVM) for classifying cats and dogs images. Experiment with different preprocessing techniques and hyperparameters to improve the model's accuracy.

Thank you for exploring PRODIGY_ML_03!
