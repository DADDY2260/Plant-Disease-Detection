# 🌿 Plant Disease Detection using CNN (MobileNetV2)

This project is a deep learning-based web application that detects plant diseases from leaf images. It uses **MobileNetV2** with **transfer learning** and was developed using **TensorFlow/Keras**. The model was trained on the **PlantVillage dataset**, and the interactive frontend is built using **Streamlit**.

---

## 📌 Features

- 🔍 Upload a leaf image and get instant disease classification
- 🧠 Utilizes MobileNetV2 for lightweight, efficient prediction
- 🧪 Built with transfer learning for better accuracy on limited data
- 🌱 Trained on real-world agricultural data (PlantVillage)
- 💻 Simple and clean web interface using Streamlit

---

## 🧠 Model Architecture

- Base Model: `MobileNetV2` (pre-trained on ImageNet)
- Custom Layers:
  - Global Average Pooling
  - Dense Layer with Softmax Activation
- Optimizer: Adam
- Loss: Categorical Crossentropy
- Evaluation Metrics: Accuracy

---

## 🧪 Dataset

- Source: [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)
- Total classes: Multiple plant species with various disease types
- Preprocessing:
  - Image resizing
  - Data augmentation (rotation, zoom, flip)

---

## 🚀 How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/DADDY2260/Plant-Disease-Detection.git
cd Plant-Disease-Detection
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the Streamlit app**
```bash
streamlit run app.py
```

4. **Upload a plant leaf image and view predictions**

> ⚠️ Note: If the model file is not included, download it from [Google Drive](#) or [Hugging Face Hub](#), and place it in the project directory.

---

## 🗂 File Structure

```
📁 Plant-Disease-Detection
├── app.py                      # Streamlit web app
├── Plant_Disease_Detection_Clean.ipynb  # Model training notebook (Colab)
├── plant_disease_model.h5      # Trained model file (external if too large)
├── requirements.txt            # Project dependencies
├── README.md                   # Project overview
└── sample_images/              # Example leaf images
```

---

## 📷 Screenshots (optional)

*Include screenshots of the web app UI here to showcase how it works*

---

## 🙋‍♂️ Author

- **GitHub**: [DADDY2260](https://github.com/DADDY2260)
- **Project**: AI-powered Agricultural Health Monitoring Tool

---

## 📜 License

This project is open-source and free to use under the MIT License.
