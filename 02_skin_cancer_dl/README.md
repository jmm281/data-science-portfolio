# Skin Cancer Classification using Deep Learning

## Objective
Development and benchmarking of multiple deep learning architectures for multiclass skin lesion classification using the HAM10000 dataset.

---

## Project Structure
This project evaluates and compares multiple CNN architectures (12 models in total), including baseline and state-of-the-art models.

Each notebook corresponds to a different experiment.

---

## Experimental Setup

Models tested include:
- Inception-based architectures
- EfficientNet variants
- Transformers

Each model was evaluated under the same preprocessing and augmentation pipeline for fair comparison.

---

## Data Processing
- Image preprocessing and normalization
- Data augmentation to mitigate class imbalance
- Train/validation/test split

---

## Results
- Best performing model achieved **92% accuracy on test set**
- Systematic comparison of 12 architectures
- Identification of best-performing CNN families for this task

---

## Technologies
Python, TensorFlow, Keras, Scikit-learn

---

## Notebooks
All experiments are located in the `/notebooks` folder, each corresponding to a specific architecture. More notebooks will be added to this repository when further testing is completed for each of them.
