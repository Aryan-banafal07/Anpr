# Automatic Number Plate Recognition (ANPR)
Automatic Number Plate Recognition (ANPR) is an advanced system designed to automatically identify and read vehicle license plates using image processing and machine learning algorithms. The project leverages TensorFlow's Object Detection API and Optical Character Recognition (OCR) technology to accurately extract and record number plates from both static images and real-time video streams.

# Features
License Plate Detection: Utilizes a pre-trained SSD MobileNet model to detect license plates in images and video.
Optical Character Recognition (OCR): Applies EasyOCR to recognize and extract text from detected license plates.
Real-Time Detection: Capable of detecting and reading license plates from a live video feed.
Model Export: Supports exporting models in TensorFlow.js and TensorFlow Lite formats for deployment in web and mobile applications.
Technologies Used
TensorFlow: Framework for building and training the object detection model.
EasyOCR: Library for performing OCR on detected license plates.
OpenCV: Library for image and video processing.
Python: Programming language used for implementation.

# Installation
Clone the Repository
git clone https://github.com/Aryan-banafal07/Anpr.git
cd Anpr

Set Up a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install Dependencies
pip install -r requirements.txt

Download Pre-trained Models and Install TensorFlow Object Detection
python setup.py

Run the Notebook

Open the Jupyter notebook and run each cell sequentially to set up paths, install necessary libraries, create label maps, generate TF records, and train and evaluate the model.


# Usage
Real-Time Detection: Run the real-time detection script to capture and analyze video from your webcam.
Image Detection: Use the notebook to load and process static images for license plate detection.
OCR Filtering: Apply OCR to extracted regions to retrieve and filter text from license plates.
Model Conversion: Convert and export the trained model to TensorFlow.js or TensorFlow Lite formats for deployment.

# Troubleshooting
Installation Issues: Ensure all dependencies are correctly installed and paths are properly set up.
Model Accuracy: Adjust thresholds and configurations in the notebook for better detection performance.
Contributing
Feel free to open issues or submit pull requests if you have suggestions or improvements.

# Contact
For questions or feedback, please contact aryanbanafal7@gmai.com.
