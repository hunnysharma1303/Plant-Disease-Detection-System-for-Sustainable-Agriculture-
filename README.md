# Plant Disease Detection System for Sustainable Agriculture

## 📌 Overview
The **Plant Disease Detection System** is a deep learning-based solution designed to identify plant diseases using image classification techniques. It leverages a pre-trained Convolutional Neural Network (CNN) model to detect various plant diseases and provide actionable insights for sustainable agriculture.

## 🚀 Problem Statement
Plant diseases can significantly impact crop yield and quality, leading to economic losses for farmers. Traditional disease detection methods are time-consuming and require expert knowledge. This project aims to provide an automated, efficient, and accessible solution for early disease detection using machine learning.

## 🎯 Objectives
- Develop an AI-based system to classify plant diseases.
- Use deep learning models to analyze plant leaf images.
- Provide accurate disease identification to assist farmers in making informed decisions.

## 📜 Literature Survey
Existing models in plant disease detection rely on image processing techniques and deep learning frameworks like CNNs. However, many of these solutions face challenges such as limited dataset availability, high computational requirements, and lack of real-time deployment capabilities. Our project addresses these gaps by optimizing model efficiency and integrating a user-friendly interface.

## 🔧 Methodology
1. **Dataset Collection**: A dataset of 87K RGB images of healthy and diseased plant leaves.
2. **Data Preprocessing**: Resizing, normalization, and augmentation.
3. **Model Training**: A CNN model trained on a well-labeled dataset.
4. **Deployment**: The model is integrated into a web-based application using Streamlit.

## 📌 System Design
- **Frontend**: Streamlit-based UI.
- **Backend**: TensorFlow-based deep learning model.
- **Database**: Image dataset stored locally or in the cloud.

## 🛠 Requirements
### Hardware
- A machine with at least 8GB RAM and a GPU (optional for faster training).

### Software
- Python
- TensorFlow
- NumPy, OpenCV, PIL
- Streamlit

## 🔗 Access Full Code
The entire project code and dataset are available in the following Google Drive folder:
[Project Code & Dataset](https://drive.google.com/drive/folders/1wGNFhdjxl7J1rljxicbArto9Z9AJT8WA)

## 📌 How to Run
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the application using `streamlit run main.py`.
4. Upload a plant image and get the disease classification results.

## 🎯 Future Enhancements
- Improve model accuracy with a larger dataset.
- Deploy as a mobile app for real-time disease detection.
- Integrate with IoT devices for automated monitoring.

---
🌱 *Empowering farmers with AI for sustainable agriculture!* 🚀

