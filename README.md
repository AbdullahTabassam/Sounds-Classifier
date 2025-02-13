# Sounds Classifier

This repository contains an AI project that uses the Sounds8k dataset from Kaggle. The project trains three types of Artificial Neural Network (ANN) models out of which one is a hyperparameter tuned model. The models are saved as .h5 files and there are four Jupyter notebooks included for Exploratory Data Analysis (EDA), Pre-processing, Training, and Evaluation. Additionally, a notebook that combines all the notebooks is also available.

## Dataset

The Sounds8k dataset is a collection of sounds, each of which is labeled with a specific category. The dataset contains 8,732 sound files distributed across 10 categories: air conditioner, car horn, children playing, dog bark, drilling, engine idling, gun shot, jackhammer, siren, and street music.

## Project Goals

The goal of this project is to classify the sounds into their respective categories using ANN models. The project trains three types of ANN models: a simple feedforward neural network, a model with neural network pruning, and a hyperparameter tuned neural network. The project aims to compare the performance of the models and determine which one performs the best.

## Project Structure

The project is organized into the following files and directories:

- README.md - This file
- models/ - Directory containing the trained ANN models in .h5 format
- notebooks/ - Directory containing the Jupyter notebooks
- EDA.ipynb - Notebook for Exploratory Data Analysis
- PreProcessing.ipynb - Notebook for Pre-processing
- Training.ipynb - Notebook for training the ANN models
- Evaluation.ipynb - Notebook for evaluating the trained models
- Sound_Classification.ipynb - Notebook that combines all the above notebooks
  
  On your device, put the jupyter notebook 'Sound_Classification.ipynb' and install the requiresd packages used in the notebook. The models trained are also available and can be used to inference you own data.

## Getting Started

To use this project, you will need to have Python 3.x and Jupyter Notebook installed. Clone the repository to your local machine and navigate to the project directory. Then install the required Python packages. To clone the repository use the following command:

git clone https://github.com/AbdullahTabassam/Sounds-Classifier

Once the packages are installed, you can open the Jupyter notebook 'Sound_Classification.ipynb' in the notebooks/ directory to perform EDA, train the models, and evaluate the models.

## Acknowledgments

This project uses the Sounds8k dataset from Kaggle. We would like to acknowledge the dataset creators for providing this dataset for use in research and education.
