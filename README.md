# Facial Emotion Recognition using ResNet

Facial Emotion Recognition (FER) is a deep learning project that aims to classify human emotions from facial expressions.
This project leverages **ResNet (Residual Neural Networks)** to achieve robust and accurate emotion recognition using the **FER-2013 dataset**.

---

## 📌 Features

* Classifies emotions into multiple categories (e.g., Angry, Happy, Sad, Fear, Surprise, Neutral, Disgust).
* Utilizes **ResNet architecture** for high accuracy and efficient training.
* Implemented in **Python** using **TensorFlow/Keras** (or PyTorch if applicable).
* Trained on the **FER-2013 dataset**.
* Can be extended for **real-time facial emotion detection** using webcam feed.

---

## 📂 Project Structure

```
├── Facial_Emotion_Recognition.ipynb   # Main Jupyter Notebook with code
├── README.md                          # Project documentation
├── requirements.txt                   # List of dependencies
└── models/                            # Saved trained models (if any)
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/facial-emotion-recognition.git
   cd facial-emotion-recognition
   ```

2. Create a virtual environment (recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

## 📊 Dataset

* **FER-2013 Dataset**: Available on [Kaggle](https://www.kaggle.com/datasets/deadskull7/fer2013).
* Contains **35,887 grayscale images** (48x48 pixels) across **7 emotion categories**:

  * Angry
  * Disgust
  * Fear
  * Happy
  * Sad
  * Surprise
  * Neutral

---

## 🏗️ Model Architecture

* **Base Model**: ResNet (Residual Neural Network)
* Input: 48x48 grayscale facial images
* Output: Emotion classification across 7 categories

The ResNet model helps avoid the **vanishing gradient problem** by using **skip connections**, enabling deeper and more accurate learning.

---

## 🚀 Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Facial_Emotion_Recognition.ipynb
   ```

2. Run the training cells to train the model (or load a pre-trained model if provided).

3. For inference:

   * Upload a facial image.
   * Run prediction to classify the emotion.

---

## 📈 Results

* Training Accuracy: 80%
* Validation Accuracy: 70%


## 🔮 Future Work

* Implement **real-time emotion recognition** using OpenCV and webcam feed.
* Improve accuracy using **data augmentation** and **transfer learning**.
* Deploy the model as a **web application** (Flask/Django/Streamlit).

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request with improvements.

---

## 📜 License

This project is licensed under the **MIT License**.
