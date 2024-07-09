# plant-disease-prediction-cnn-deep-leanring-project
This repository is about building an Image classifier CNN with Python on Plant Disease Prediction.

Kaggle Dataset Link: https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

Trained Model Link: [[https://drive.google.com/file/d/1i466c4XOs048Q54EPCqgzoG8zWcARnrj/view?usp=sharing](https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=sharing)](https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link)https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link

Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/dhirajk27/Plant-Disease-Prediction-CNN-DEEP-Learning-Project-.git
cd Plant-Disease-Prediction-CNN-DEEP-Learning-Project-
Create a Virtual Environment:

bash
Copy code
python -m venv venv
Activate the Virtual Environment:

For Windows:
bash
Copy code
.\venv\Scripts\activate
For macOS/Linux:
bash
Copy code
source venv/bin/activate
Install the Required Packages:

bash
Copy code
pip install -r app/requirements.txt
Data Preparation
Download the Dataset:
Download a plant disease dataset. You can use the PlantVillage dataset or any other dataset available online.

Organize the Dataset:
Place the dataset in the data directory. Ensure the data is organized in subdirectories, each representing a different class of disease.

Model Training
Navigate to the Source Directory:

bash
Copy code
cd src
Run the Training Script:

bash
Copy code
python train.py
This script will train the CNN model on the dataset and save the trained model to the models directory.

Model Evaluation
Evaluate the Model:
You can evaluate the trained model using the test dataset by running the evaluation code in the notebooks directory or by extending the train.py script to include evaluation metrics.
Running the Application
Navigate to the Application Directory:

bash
Copy code
cd app
Run the Streamlit Application:

bash
Copy code
streamlit run main.py
Access the Web Interface:
Open a web browser and go to http://localhost:8501 to interact with the application. You can upload images of plant leaves, and the app will predict the disease.

References
TensorFlow
Keras
Streamlit
PlantVillage Dataset

