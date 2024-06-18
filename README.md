# PRODIGY_ML_03 - Image Classifier using Support Vector Machine (SVM)

Title: Cat-Dog Image Classifier using SVM Description: This repository contains code for building a Support Vector Machine (SVM) model to classify images of cats and dogs from the Kaggle dataset. The SVM model is trained on a labeled dataset of cat and dog images to predict the class of new images as either cat or dog.

Welcome to PRODIGY_ML_03! This project implements an image classifier using Support Vector Machine (SVM) for the task of classifying images of cats and dogs from the Kaggle dataset.

## Project Structure

- `data/`: Contains the dataset of cats and dogs images.
- `src/`: Contains the source code for data preprocessing, model training, and evaluation.
- `README.md`: The main documentation file you're currently reading.

## Prerequisites

- Python 3
- Jupyter Notebook
- Required Python libraries: numpy, pandas, matplotlib, scikit-learn, Pillow, tqdm

## Getting Started

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/astromanu007/PRODIGY_ML_03.git
   ```

2. Download the Kaggle "Cats and Dogs" dataset from [here]([https://www.kaggle.com/c/dogs-vs-cats/data](https://www.kaggle.com/datasets/tongpython/cat-and-dog)) and extract it into the `data/` folder.

3. Open a terminal and navigate to the project directory:
   ```
   cd PRODIGY_ML_03
   ```

4. Install the required Python libraries if you haven't already:
   ```
   pip install -r requirements.txt
   ```

## Data Preprocessing

1. Preprocess the images by resizing them and converting to grayscale.

2. Load and preprocess the dataset using the Jupyter Notebook provided in the `src/` directory.

## Training the SVM Model

1. Split the dataset into training and testing sets.

2. Initialize and train the SVM classifier using the provided code in the Jupyter Notebook.

## Evaluating the Model

1. Calculate the accuracy of the model on the test set.

2. Visualize sample predictions to evaluate the model's performance.

## Conclusion

This project demonstrates the implementation of an image classifier using Support Vector Machine (SVM) for classifying cats and dogs images. Experiment with different preprocessing techniques and hyperparameters to improve the model's accuracy.

Thank you for exploring PRODIGY_ML_03!

---

Feel free to customize this README further to include specific details about your project or any additional sections you find necessary. Let me know if there's anything else I can assist you with!
