# Rice Classification with CNN

## 📌 Overview

This project is a Convolutional Neural Network (CNN) model built with TensorFlow & Keras to classify different types of rice grains. The dataset consists of five categories:

- **Arborio**
- **Basmati**
- **Ipsala**
- **Jasmine**
- **Karacadag**

The model is trained on images resized to 128x128 pixels, and it is saved in multiple formats for deployment.

## 📂 Project Structure

```
├── rice_classification.ipynb  # Jupyter Notebook containing all code
├── dataset/                   # Dataset folder
├── saved_model/               # TensorFlow SavedModel format
├── tflite/                    # TensorFlow Lite format
├── tfjs_model/                # TensorFlow.js format
├── requirements.txt           # List of required dependencies
└── README.md                  # Project documentation
```

## 🔧 Setup & Dependencies

### 1️⃣ Install Required Libraries

Ensure you have Python installed, then install dependencies using:

```bash
pip install -r requirements.txt
```

## 📥 Dataset

The dataset contains images categorized into different rice types.

- Images are resized, normalized, and prepared for deep learning training.

## 🚀 Model Training & Evaluation

### 1️⃣ Load & Preprocess Data

- Load images and assign labels.
- Resize images to 128x128 pixels.
- Normalize pixel values between 0 and 1.
- Split dataset into training, validation, and testing sets.

### 2️⃣ Build CNN Model

A Convolutional Neural Network (CNN) is constructed with multiple convolutional layers, pooling layers, and fully connected layers to classify the rice images.

### 3️⃣ Train the Model

Run the Jupyter Notebook to train the model:

```bash
jupyter notebook rice_classification.ipynb
```

- Train the model inside the notebook.

### 4️⃣ Evaluate the Model

The trained model is evaluated on the test set to determine its accuracy and performance.

## 🎯 Model Saving & Deployment

✅ **Save in TensorFlow SavedModel Format**

- The trained model is saved in the TensorFlow SavedModel format.

✅ **Convert to TensorFlow Lite**

- The model is converted into TensorFlow Lite format for mobile and edge deployment.

✅ **Convert to TensorFlow.js Format**

- The model is also converted to TensorFlow.js format for web-based applications.

## 📊 Visualization

### 🔹 Data Distribution

- A bar chart is created to visualize the dataset distribution before training.

### 🔹 Training Accuracy & Loss

- A line plot tracks accuracy over training epochs.
- Another plot visualizes loss values to monitor learning progress.

## 📥 Download the Model

All trained model formats are compressed into a zip file for easy download.
Run the following command in the notebook to create and download the zip file:

```bash
!zip -r rice_model.zip saved_model tflite tfjs_model
```

## 📌 Conclusion

- A CNN model is trained to classify rice grains with high accuracy.
- The trained model is stored in various formats for flexible deployment.
- Data visualization provides insights into dataset distribution and model performance.
- The final model is made available for download.

🎯 **This project enables efficient rice grain classification using deep learning! 🚀**
