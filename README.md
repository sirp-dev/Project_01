# Data Leakage Prevention System using AI and Neural Networks

This project demonstrates a system designed to detect and prevent data leakage in real-time using Artificial Intelligence (AI) and Neural Networks (NN). It applies techniques such as differential privacy, federated learning, and membership inference attacks to safeguard sensitive data.

## Folder Structure
- `data/`: Contains the dataset files.
- `models/`: Stores the trained models.
- `scripts/`: Python scripts for training, evaluating, and detecting data leakage.
- `notebooks/`: Jupyter notebooks for model development and experimentation.

## Prerequisites

Before running the project, ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt


## Running the Project

### Step 1: Data Preparation
Place your dataset in the `data/` folder. Ensure the dataset is clean and preprocessed before training the model.

### Step 2: Train the Model
Run the `train_model.py` script to train the neural network model on your dataset.

```bash
python scripts/train_model.py
