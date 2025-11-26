# Cat Breed Classifier

A machine learning project for training a cat breed classification model using Keras and TensorFlow.

## Requirements

- Python 3.10.11
- Jupyter Notebook

## Features

- **Data preprocessing**: Loads and prepares cat breed images for training.
- **Model training**: Builds and trains a convolutional neural network (CNN) for cat breed classification.
- **Model evaluation**: Tests model accuracy and generates performance metrics.
- **Export model**: Saves the trained model as `.keras` file for deployment.

## Getting Started

1. Navigate to the project folder:
   ```bash
   cd cat_classifier_training
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open `train_model.ipynb` and run all cells to train the model.

6. The trained model will be saved in the `models/` folder.

## License

This project is licensed under the MIT License.
