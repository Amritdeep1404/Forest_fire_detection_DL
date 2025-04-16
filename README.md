# Forest_fire_detection_DL
This project aims to develop an intelligent forest fire detection system using deep learning to provide early warnings and minimize wildfire damage. 
# Demo
A sample image classification result using the trained model
# features 
1.Image classification using a CNN model.
2.Classifies images as **"Fire"** or **"No Fire"**.
3.Simple, scalable architecture.
4.Can be deployed on edge devices for real-time detection.
#The dataset consists of images labeled as:
- `Fire`
- `No Fire`

You can use the [Kaggle Forest Fire Image Dataset](https://kaggle/input/the-wildfire-dataset) or build a custom dataset using images from open sources.
# Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib
- Jupyter Notebook / Google Colab
#installation

 Clone the repository:
   ```bash
   git clone https://github.com/your-Amritdeep1404/forest-fire-detection.git
   cd forest-fire-detection
# How It Works
Data Preprocessing
Images are resized, normalized, and augmented for training.

Model Architecture
A simple CNN with convolution, pooling, and dense layers.

Training
The model is trained to classify images as fire or non-fire.

Prediction
New images can be passed to the model for real-time fire detection. 
