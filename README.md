* CNN Image Classification Using MNIST Dataset

** Project Overview
This project focuses on handwritten digit recognition using a Convolutional Neural Network (CNN). The MNIST dataset is used to train and evaluate the model to identify handwritten digits from 0 to 9.

** Objectives
- Understand and explore the MNIST dataset.
- Preprocess handwritten digit images.
- Build and train a CNN model.
- Evaluate the model using test data.
- Compare actual and predicted digit labels.
- Explore the use of Streamlit for developing an interactive application.

** Dataset Description
**Dataset Name:** MNIST Handwritten Digits Dataset

The MNIST dataset contains:
- 60,000 training images.
- 10,000 testing images.
- 10 different classes (digits 0–9).
- Image dimensions: 28 × 28 pixels.
- Grayscale images.

The dataset is loaded using TensorFlow/Keras, so manual downloading is not required.

**Technologies and Libraries Used
- Python
- Google Colab
- TensorFlow and Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Streamlit

***CNN Workflow

*** 1. Import Libraries
Import the required Python libraries for data processing, visualization, and deep learning.

*** 2. Load Dataset
Load the MNIST dataset using `mnist.load_data()`.

*** 3. Explore Dataset
Check the dataset shapes, number of classes, training samples, and testing samples.

*** 4. Visualize Images
Display sample handwritten digit images with their corresponding labels.

*** 5. Data Preprocessing
- Normalize pixel values between 0 and 1.
- Reshape images into the format required by the CNN model.

***6. Build CNN Model
The CNN architecture includes:
- Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layer
- Dropout layer
- Output layer with 10 neurons

*** 7. Compile and Train
The model is compiled using:
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Metric: Accuracy
- Epochs: 5
- Batch Size: 64
- Validation Split: 10%

 8. Model Evaluation
Evaluate the trained model using the testing dataset and calculate test loss and accuracy.

*** 9. Prediction
Predict handwritten digits and compare actual labels with predicted labels.

** Results
The model's performance is evaluated using test accuracy and test loss. Correct and incorrect predictions are also counted and visualized.

*Add your actual model accuracy and screenshots after running the notebook.*

** Streamlit Application
Streamlit is included in the project requirements for creating an interactive web application.

**Note:** The uploaded notebook currently contains Streamlit installation and import steps, but the actual Streamlit application code still needs to be added.

** How to Run the Project
1. Open Google Colab.
2. Upload `CNN.ipynb`.
3. Run the notebook cells in order.
4. Allow TensorFlow/Keras to load the MNIST dataset.
5. Train and evaluate the CNN model.
6. View the prediction results and visualizations.

** Conclusion
This project demonstrates how Convolutional Neural Networks can be used for handwritten digit classification. It provides practical experience in dataset exploration, image preprocessing, model building, training, evaluation, and prediction.

**Future Improvements
- Increase the number of training epochs.
- Experiment with different CNN architectures.
- Improve model accuracy.
- Develop an interactive Streamlit application for user-friendly predictions.
**Author**

Name: Laxmipriya Nayak
Branch: CSE
Batch: OCT(B)
