# 🚗 Car Brand Classifier – BMW vs Audi vs Mercedes

This project is a beginner-friendly machine learning model that classifies images of cars as **BMW**, **Audi**, or **Mercedes-Benz** based on full-car photos (not just logos). It uses deep learning (CNNs and transfer learning) to learn visual features from real-world car images, making it suitable for mobile or web-based applications.

---

## 📌 Project Overview

- **Type:** Image Classification (Multi-class)
- **Classes:** BMW, Audi, Mercedes-Benz
- **Framework:** TensorFlow / Keras
- **Goal:** Given a photo of a car, predict whether it is a BMW, Audi, or Mercedes-Benz.

---

## 🧠 How It Works

1. A dataset of car images is collected manually from the internet.
2. The images are cleaned and resized for uniformity.
3. A Convolutional Neural Network (CNN) is built using **transfer learning** (e.g., MobileNetV2 or ResNet50).
4. The model is trained and validated on the dataset.
5. The trained model is used to classify new car images.

---

## 🗂️ Folder Structure

car-brand-classifier/
│
├── dataset/ # Local dataset (NOT included in the repo)
│ ├── audi/
│ ├── bmw/
│ └── mercedes/
│
├── models/ # (Optional) Saved trained model files
│
├── notebooks/ # Jupyter Notebooks (EDA, training, evaluation)
│
├── src/ # Python scripts (data loader, training, prediction)
│
├── .gitignore
├── README.md
├── requirements.txt
└── train.py # Entry point for training the model


---

## 🖼️ Dataset

The dataset consists of manually collected images of three brands:

- **BMW**  
- **Audi**  
- **Mercedes-Benz**

Images were gathered from Google Images, car dealership websites, and forums. Each folder should contain a variety of models and angles (front, side, rear).

Due to size and licensing constraints, the dataset is **not included in this repository**. You can recreate the dataset by following this structure:

/dataset
    /audi
    audi1.jpg
...
    /bmw
    bmw1.jpg
...
    /mercedes
    mercedes1.jpg




## 🔧 Installation

``` bash
# Clone the repository
git clone https://github.com/yourusername/car-brand-classifier.git
cd car-brand-classifier

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

```
