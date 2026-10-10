# 🌿 Plant Disease Prediction Using CNN

![Plant Disease Classification](HeaderImage.png)

## 📌 Project Overview

Plant diseases are a major challenge in agriculture, affecting crop quality, productivity, and overall yield. Early identification of plant diseases can help farmers take preventive measures and minimize crop losses.

**Plant Disease Prediction Using CNN** is an AI/ML project that uses a Convolutional Neural Network (CNN) to classify plant diseases from leaf images. The project includes a Python implementation, a Jupyter Notebook for model development and experimentation, test images for prediction, and a trained CNN model available for download.

The main goal is to demonstrate how deep learning and image classification can be applied to agricultural disease detection.

## 🎯 Objectives

- Detect and classify plant diseases from leaf images.
- Apply deep learning techniques to image classification.
- Explore CNN-based plant disease prediction.
- Enable predictions on new plant leaf images.
- Demonstrate the application of AI in smart agriculture.

## ✨ Key Features

- 🌱 Plant leaf image classification.
- 🧠 CNN-based deep learning approach.
- 🖼️ Test images for evaluating predictions.
- 🐍 Python implementation for plant disease prediction.
- 📓 Jupyter Notebook for experimentation and model development.
- 📦 Downloadable CNN model.
- 📊 Supporting project presentation.

## 🛠️ Technologies Used

- **Python** — Core programming language.
- **Convolutional Neural Network (CNN)** — Image classification.
- **Deep Learning** — Learning visual patterns associated with plant diseases.
- **Jupyter Notebook** — Model development and experimentation.
- **Image Processing** — Preparing leaf images for prediction.

The specific Python libraries and their versions should be verified from the source code and notebook.

## 📂 Project Structure

```text
PlantDiseaseClassification_AIML/
│
├── Test Images/
│   └── Sample plant leaf images
│
├── Download CNN model here
│   └── Link to download the trained model
│
├── HeaderImage.png
│
├── Plant Disease Prediction (PPT).pptx
│
├── Plant Disease Prediction.py
│
├── PlantDiseasePrediction.ipynb
│
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/mananvernekar07/PlantDiseaseClassification_AIML.git
```

### 2. Navigate to the project directory

```bash
cd PlantDiseaseClassification_AIML
```

### 3. Install the required dependencies

Install the Python libraries required by the project:

```bash
python -m pip install streamlit tensorflow numpy opencv-python pillow
```

**Note:** Install the TensorFlow version compatible with your Python environment and the model. The required packages may differ depending on the implementation.

## 🚀 How to Run the Project

### Run the Python script

Run the prediction script from the project directory:

```bash
python -m streamlit run "Plant Disease Prediction.py"
```

Follow the instructions in the script, if any, to load the CNN model and provide a plant leaf image.


## 🧠 How It Works

The general CNN-based classification workflow consists of the following steps:

1. **Image Input:** Load an image of a plant leaf.
2. **Preprocessing:** Resize and prepare the image according to the model's input requirements.
3. **Feature Extraction:** CNN layers learn visual features such as shapes, textures, and disease-related patterns.
4. **Classification:** The trained network predicts a class from the categories it was trained to recognize.
5. **Prediction Output:** Display the predicted class or disease label.

The exact preprocessing steps, architecture, and output categories depend on the implementation in the Python script and notebook.

## 📦 Trained CNN Model

The repository provides a **Download CNN model here** entry for accessing the trained model.

To use the trained model:

1. Open the model download entry in the repository.
2. Follow the provided download instructions.
3. Download the model file.
4. Place it in the location expected by the Python script or notebook.
5. Ensure the model-loading path in the code matches the downloaded file.

Refer to the source code for the expected model format and file path.

## 🧪 Testing

The `Test Images` directory contains sample images intended for testing the prediction workflow.

Testing can help verify that:

- Images are loaded correctly.
- Preprocessing matches the model's expected input format.
- The trained model loads successfully.
- Predictions are produced for supported plant categories.

For reliable evaluation, use a separate labeled test dataset and report metrics such as accuracy, precision, recall, and F1-score when available.

## 🌾 Applications

- Early screening of plant diseases.
- Agricultural research and experimentation.
- AI-assisted crop monitoring.
- Smart farming and precision agriculture.
- Educational demonstrations of deep learning and computer vision.

## 🔮 Future Enhancements

- Develop a web interface for uploading plant leaf images.
- Build a mobile application for field-based disease screening.
- Expand the number of supported plant species and diseases.
- Evaluate and compare different CNN architectures.
- Add disease-specific guidance using reliable agricultural resources.
- Deploy the model for easier access by farmers and agricultural professionals.

## ⚠️ Limitations

- Predictions depend on the quality and diversity of the training data.
- The model may perform differently on images captured under real-world conditions.
- Visually similar diseases may be difficult to distinguish.
- Predictions are intended for preliminary screening and should not replace expert agricultural diagnosis.

## 👨‍💻 Author

**Manan Vernekar**

GitHub: [@mananvernekar07](https://github.com/mananvernekar07)

## 📂 Repository Link

[PlantDiseaseClassification_AIML — GitHub](https://github.com/mananvernekar07/PlantDiseaseClassification_AIML)

## 📚 Dataset Reference
Dataset Link: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset/

## 📄 License

Please check the repository for a license file before reusing, modifying, or distributing this project.

---

⭐ If you find this project useful, consider giving the repository a star!

