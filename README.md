# Image-Classifier
Image Classification System Using Convolutional Neural Networks (CNNs)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Introduction
This project implements an image classification system using Convolutional Neural Networks (CNNs). It allows users to classify images into predefined categories with a trained CNN model.

## Features
- Image classification using a trained CNN model
- Web interface for uploading and classifying images
- Interactive Jupyter Notebook for model training

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/viveknair6915/Image-Classifier.git
    cd Image-Classifier
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Train the model:
    - Open `Model_Train.ipynb` in Jupyter Notebook.
    - Follow the steps in the notebook to train the CNN model on your dataset.

2. Run the web application:
    ```bash
    python app.py
    ```

3. Open your web browser and go to `http://localhost:5000`.

## Project Structure
- `static/`: Contains static files (e.g., CSS, images).
- `templates/`: Contains HTML templates for the web application.
- `Model_Train.ipynb`: Jupyter Notebook for training the CNN model.
- `app.py`: Flask web application script.
