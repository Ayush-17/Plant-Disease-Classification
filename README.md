Plant Disease Classification

📌 Project Overview

This project aims to classify plant diseases using a deep learning model. The model is trained on a dataset of plant leaf images and can predict various plant diseases with high accuracy.

🚀 Features

Uses deep learning for image-based disease classification

Trained on a dataset of plant leaf images

Supports multiple plant disease categories

Provides accurate predictions for early disease detection

🛠️ Tech Stack

Python

TensorFlow / Keras

OpenCV

Flask (if deployed as a web application)

Git LFS (for managing large model files)

📂 Project Structure

Plant Disease Classification/
│-- dataset/  # Contains plant leaf images
│-- models/   # Trained models stored here
│-- notebooks/  # Jupyter notebooks for training and testing
│-- app.py  # Flask or main script for inference
│-- trained_plant_disease_model.keras  # Trained model (tracked via Git LFS)
│-- requirements.txt  # Required dependencies
│-- README.md  # Project documentation

🔧 Setup Instructions

Clone the repository:

git clone https://github.com/Ayush-17/Plant-Disease-Classification.git
cd Plant-Disease-Classification

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Download LFS-tracked files (if not present locally):

git lfs pull

Run the model for predictions:

python app.py

📊 Model Training

The model is trained on a dataset of plant leaf images.

Uses CNN (Convolutional Neural Networks) for feature extraction.

Augmentation techniques are applied for better generalization.

Evaluation metrics include accuracy, precision, and recall.

🤝 Contribution

Feel free to contribute by submitting a PR or reporting issues!

📜 License

This project is licensed under the MIT License.

