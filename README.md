# Drowniness-Detection-System
A real-time driver drowsiness detection system implemented in a Jupyter Notebook (drowniness_detection_system.ipynb). The system uses a Vision Transformer (ViT)–based model along with traditional computer vision techniques to detect signs of drowsiness—such as prolonged eye closure and yawning—from a live webcam feed or recorded video.

# 📋 Dataset
This project was developed and tested on the NTHU Drowsy Driver Detection Dataset (or an equivalent public drowsiness dataset). It contains labeled video sequences of drivers exhibiting normal, sleepy, and yawning states.

Download link (example): https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd


# 🚀 Installation & Setup

1. Clone or download this repository.

2. Install required packages and Liberaries (if running locally):

3. Open drowniness_detection_system.ipynb in your Jupyter environment.

# Note - This project was developed and run on Kaggle Notebooks. No manual installation is required if you open and run it directly there.

# 🛠️ Technologies & Libraries

Python 3.8+

TensorFlow / Keras – for model definition and training

OpenCV – for video capture and frame processing

dlib / imutils – for facial landmark detection

Vision Transformer (ViT) – backbone network for feature extraction

Matplotlib – for plotting training curves and sample predictions



# 📌 Usage

1. Load the dataset by updating the dataset path in the first notebook cell.

2. Preprocess video frames to extract eye and mouth regions using facial landmarks.

3. Build and train the ViT-based drowsiness detection model (cells include hyperparameter settings).

4. Run inference on live webcam feed or test video:

    - The notebook will draw bounding boxes around detected faces and overlay drowsiness status.

5. Visualize results with plots of accuracy, loss, and example frames.

Simply run all cells from top to bottom to reproduce the complete pipeline.


