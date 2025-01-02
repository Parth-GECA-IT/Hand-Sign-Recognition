# ✋Hand Sign Recognition System

This project demonstrates a Hand Sign Recognition system using Python, TensorFlow, OpenCV, and MediaPipe. It identifies and processes hand gestures to classify or analyze them for various applications, such as sign language recognition.

## 🌟 Features
- **Real-time Hand Gesture Recognition**: Leverages MediaPipe's holistic model for real-time hand and body keypoint detection.
- **Machine Learning Integration**: Uses TensorFlow for gesture classification.
- **Visualization**: Includes matplotlib for graphical representation of keypoints.

---

## ⚙️ Requirements

### Dependencies
Install the required libraries using pip:
```bash
pip install tensorflow==2.13.0rc0 tensorflow-gpu==2.12.0 opencv-python mediapipe sklearn matplotlib
```

### Hardware
- Webcam for real-time video capture.
- GPU support (optional but recommended for faster performance).

---

## 📩 Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Parth-GECA-IT/Hand-Sign-Recognition.git
cd Hand-Sign-Recognition
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Prepare Dataset
This project assumes that you will collect data for various hand gestures:
- **Keypoints**: Extracted using MediaPipe Holistic.
- **Labels**: Assigned for each gesture class.

Run the script for keypoint extraction and dataset generation.

### 4. Train the Model
Use TensorFlow to train a machine learning model on the extracted keypoints. The notebook provides the necessary code to:
- Preprocess the dataset.
- Train and save the model.

---

## 🪴 Usage

### 1. Run the Hand Recognition System
Run the Python script or cells in the Jupyter Notebook:
```bash
python HandSignFinal.py
```

### 2. Real-time Gesture Recognition
The system will capture video from the webcam, process frames using MediaPipe, and classify hand gestures in real-time.

### 3. Visualize Results
Graphs and keypoint visualizations are generated in real-time or as post-processing steps.

---

## 📂 Project Structure
- **HandSignFinal.ipynb**: Main notebook with code for installation, keypoint extraction, training, and inference.
- **requirements.txt**: Dependencies for the project.
- **model/**: Directory to save trained models.
- **dataset/**: Contains the collected keypoints and labels.

---

## 🔮 Future Work
- **Expand Gesture Dataset**: Collect more samples for diverse hand gestures.
- **Optimize for Edge Devices**: Deploy the model on mobile or embedded devices.
- **Integration with Applications**: Use the recognition system for accessibility tools, gaming, or robotics.

---

## 🅰️ Acknowledgments
- [MediaPipe by Google](https://mediapipe.dev/): For holistic keypoint detection.
- [TensorFlow](https://www.tensorflow.org/): For machine learning and model training.

---

## 🪪 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 👥 Contributors

- **Parth Armarkar** - [LinkedIn](http://www.linkedin.com/in/parth-armarkar-052551289) | [GitHub](https://github.com/Parth-GECA-IT)
- **Karan Gawande** - [LinkedIn](linkedin.com/in/karan-gawande-64aa3b231) | [GitHub](https://github.com)
- **Dhruv Punekar** - [LinkedIn](https://www.linkedin.com/in/dhruv-punekar-a57299277/) | [GitHub](https://github.com)
- **Prakhar Singh** - [LinkedIn](https://www.linkedin.com/in/prakhar-singh-1b9614185/) | [GitHub](https://github.com/prakharsingh1923)