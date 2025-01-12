# Plant Disease Detection System for Sustainable Agriculture

## Overview
This project is a deep learning-based web application designed to detect plant diseases from images. By leveraging TensorFlow and Streamlit, the system provides an intuitive and accurate tool to assist farmers in identifying plant diseases and adopting timely interventions. The primary goal is to support sustainable agriculture practices by reducing crop loss and optimizing disease management strategies.

## Features
- *Disease Detection*: Identifies a variety of plant diseases from uploaded leaf images.
- *User-Friendly Interface*: Accessible web-based application built with Streamlit.
- *Interactive Visuals*: Displays uploaded images and predicts the detected disease.
- *Real-Time Prediction*: Provides quick results based on uploaded images.
- *Wide Coverage*: Recognizes diseases across multiple crops like Apple, Tomato, Corn, Potato, and more.

## Technologies Used
- *Programming Language*: Python
- *Frameworks*:
  - TensorFlow for deep learning model development
  - Streamlit for creating the web interface
- *Libraries*:
  - NumPy
  - PIL (Python Imaging Library)
  - TensorFlow's preprocessing utilities
- *Tools*: Jupyter Notebook for training and testing the model

## Dataset
The model is trained on a dataset containing labeled images of healthy and diseased plants. Each image corresponds to a specific crop and disease category. The dataset ensures diverse representation to generalize the model's predictions.

## Installation and Setup
### Prerequisites
Ensure the following are installed:
- Python 3.8 or later
- Pip package manager

### Steps to Run
1. Clone the repository:
   bash
   git clone <repository-url>
   
2. Navigate to the project directory:
   bash
   cd plant-disease-detection
   
3. Install required dependencies:
   bash
   pip install -r requirements.txt
   
4. Run the Streamlit application:
   bash
   streamlit run main.py
   
5. Open the application in your browser (default: http://localhost:8501).

## How to Use
1. Launch the application and navigate to the "Disease Recognition" page.
2. Upload a clear image of the plant leaf.
3. Click on "Predict" to view the disease classification.
4. The system displays the most likely disease and highlights relevant information.

## Future Work
- *Improved Accuracy*: Experiment with more advanced neural networks like EfficientNet.
- *Edge Deployment*: Implement the model on IoT devices for real-time field analysis.
- *Expanded Dataset*: Incorporate more crop varieties and diseases to increase versatility.
- *Mobile App*: Develop a mobile application for better accessibility.

## Contribution Guidelines
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a feature branch:
   bash
   git checkout -b feature-name
   
3. Commit your changes:
   bash
   git commit -m "Description of changes"
   
4. Push to the branch:
   bash
   git push origin feature-name
   
5. Submit a pull request.

## Acknowledgements
- The TensorFlow team for their robust tools and documentation.
- Streamlit for simplifying web app development.
- The creators of the dataset used for model training.

