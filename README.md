
# 🤖 Face Recognition ML Model

A face recognition system built using **OpenCV**, **TensorFlow**, and **Keras** that detects and recognizes faces in real-time via webcam or from stored images. This project demonstrates how computer vision and deep learning can be used to build reliable face recognition applications.

---

## 🧠 How It Works

1. **Data Collection**: Captures and stores multiple face samples of users.
2. **Model Training**: Trains a Convolutional Neural Network (CNN) on the collected face data.
3. **Face Detection**: Uses OpenCV’s Haar Cascade Classifier to detect faces.
4. **Face Recognition**: Classifies the face using the trained model and displays the recognized user.

---

## 📦 Tech Stack

- 🧠 **TensorFlow** & **Keras** — for training the recognition model
- 📸 **OpenCV** — for image capture and face detection
- 🐍 **Python** — backend scripting
- 🗂️ **Numpy, OS, Pickle** — for data handling and preprocessing

---

## 🗃️ Project Structure

```

Face-Recognition-ML-Model/
├── data/                    # Stores captured face images
├── dataset/                # Processed dataset for training
├── model/                  # Trained model files
├── train\_model.py          # Trains the CNN model
├── collect\_faces.py        # Captures face data via webcam
├── recognize.py            # Runs real-time face recognition
├── README.md

````

---

## 🔧 How to Use

### 1. Clone the repository
```bash
git clone https://github.com/Astha132005/Face-Recognition-ML-Model.git
cd Face-Recognition-ML-Model
````

### 2. Install dependencies

```bash
pip install opencv-python numpy tensorflow keras
```

### 3. Collect face data

```bash
python collect_faces.py
```

Follow the on-screen instructions to record your face samples.

### 4. Train the model

```bash
python train_model.py
```

### 5. Run real-time recognition

```bash
python recognize.py
```

---

## 📽️ Demo

> Coming soon: video walkthrough & sample predictions

---

## 🙋‍♀️ About Me

**Astha Dakhinray**
B.Tech CSE (AIML) | ML Enthusiast | Front-End Developer
📎 [LinkedIn](https://www.linkedin.com/in/astha-dakhinray-02b0852a0/)
📎 [GitHub](https://github.com/Astha132005)
📎 [Portfolio](https://astha132005.github.io/3D-Portfolio/)

---

## 📌 Disclaimer

This project is for educational use only. Not intended for security or commercial deployment.

---

## 🌟 Support

If you found this project helpful, **give it a star** ⭐ and share it!

```

---

Would you like:
- A matching **15-second demo video** preview block?
- A `requirements.txt` for easy setup?
- A section for model performance/metrics?

I can add those for you!
```
