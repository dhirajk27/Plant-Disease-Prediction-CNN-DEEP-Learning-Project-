
# Plant Disease Prediction using CNN and Deep Learning

This repository is about building an Image classifier CNN with Python on Plant Disease Prediction.

- Kaggle Dataset Link: [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)
- Trained Model Link: [Download Trained Model](https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link)

## Table of Contents
- [Installation](#installation)
- [Data Preparation](#data-preparation)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Running the Application](#running-the-application)
- [References](#references)

## Installation

### 1.Clone the Repository:
```bash
git clone https://github.com/dhirajk27/Plant-Disease-Prediction-CNN-DEEP-Learning-Project-.git
cd Plant-Disease-Prediction-CNN-DEEP-Learning-Project-
```

### 2.Create a Virtual Environment:
```bash
python -m venv venv
```

### 3.Activate the Virtual Environment:
For Windows
```bash
.\venv\Scripts\activate
```
For macOS/Linux
```bash
source venv/bin/activate
```

### 4.Install the Required Packages:
```bash 
pip install -r app/requirements.txt
```

## Data-Preparation
1.Download the Dataset:
Download a plant disease dataset. You can use the PlantVillage dataset or any other dataset available online.

2.Organize the Dataset:
Place the dataset in the data directory. Ensure the data is organized in subdirectories, each representing a different class of disease.

## Model Evaluation

1.Evaluate the Model:
You can evaluate the trained model using the test dataset by running the evaluation code in the `notebooks` directory or by extending the `train.py` script to include evaluation metrics.

## Running the Application

1.Navigate to the Application Directory:
```bash
cd app
```

2.Run the Streamlit Application:
```bash
streamlit run main.py
```

3.Access the Web Interface:
Open a web browser and go to http://localhost:8501 to interact with the application. You can upload images of plant leaves, and the app will predict the disease.

