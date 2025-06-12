# HIMU
This project focuses on intention classification, which aims to determine whether a person’s expressed intention (via speech, text, or behavior) matches their actual intention. It leverages a multi-modal deep learning model that integrates information from:

📝 Text (spoken/written content)

🔊 Audio (tone, pitch, speech patterns)

🎥 Video (facial expressions, gestures)

The developed model achieves an accuracy of 78.83%, showcasing its potential in understanding complex human behavior through multi-modal signals.

🗂️ Project Structure
All files related to this project are located in the intention_identification/ directory.

📁 Datasets
Includes both raw and preprocessed datasets required for training and testing.

📒 Notebooks
demo_project.ipynb

Full training pipeline: data loading, preprocessing, model building, training, and evaluation.

Use this notebook if you want to train the model from scratch or fine-tune it.

demo_intention_identification.ipynb

Inference pipeline for testing the trained model on video samples.

Ideal for running predictions on new inputs and validating results.

⚙️ Getting Started
You can run the notebooks using:

Jupyter Notebook (locally) – Installation Guide

Google Colab (cloud-based, no setup required) – Open in Colab

Ensure all dependencies (e.g., torch, transformers, opencv, etc.) are installed before execution. GPU acceleration is highly recommended for training and real-time inference.

📈 Model Performance
Accuracy Achieved: 78.83%

Trained on multi-modal inputs for robust classification
