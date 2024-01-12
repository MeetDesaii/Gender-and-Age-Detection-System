# Gender-and-Age-Detection-System


### Introduction

• Welcome to the Gender and Age Detection System project! This system is designed to accurately identify the gender and age of individuals in a given image. Utilizing state-of-the-art machine learning models and leveraging the power of OpenCV, this guide aims to provide you with all the information you need to understand, use, or contribute to this project. 

Read the given information for a better understanding of this project.


### Models Used

**1. Face Detection:** A pre-trained OpenCV DNN model (opencv_face_detector) is used for detecting faces in images.

**2. Age Classification:** A Caffe model (age_net.caffemodel) trained on the Adience dataset is employed for age detection.

**3. Gender Classification:** Another Caffe model (gender_net.caffemodel) is used for gender detection.


### File Structure

• **models/:** This folder contains all the pre-trained models.

    opencv_face_detector.pbtxt
    opencv_face_detector_uint8.pb
    age_deploy.prototxt
    age_net.caffemodel
    gender_deploy.prototxt
    gender_net.caffemodel

• **sample_images/:** Place your test images in this folder.


### Technologies Used

• **Python:** The backbone of our project, used for scripting and data manipulation.

• **OpenCV:** Open Source Computer Vision Library, utilized for image processing tasks and DNN functionalities.

• **Caffe:** Deep learning framework, the format in which our age and gender classifiers are saved.


### Required Tools

• **Python 3.x:** The code is written in Python 3.

• **Jupyter Notebook or Google Colab:** For an interactive experience, you can use Jupyter Notebook or Google Colab to run the code blocks.

• **IDE/Text Editor:** Any text editor or IDE capable of handling Python files, like VSCode, PyCharm, or Sublime Text.


### Required Packages

• **cv2:** OpenCV library for Python, for all image processing needs.

• **math:** (Optional) For mathematical operations.

• **time:** To track the time taken by different code blocks.


  • You can install the required packages using pip:

  ```
  pip install opencv-python
  ```


### Error Handling

• I have integrated robust error handling using if-else statements to ensure that the system can gracefully handle file and data inconsistencies, thereby providing a smooth and reliable user experience.

  ```
  if input is None:
    print("Image not found or not readable.")
  else:
      # Continue with processing
  ```
This conditional checking ensures that only valid, accessible files are processed, aiding in both debugging and data integrity.


### Installation

1. Clone the Repository

  ```
  git clone https://github.com/MeetDesaii/Gender-and-Age-Detection-System.git
  ```


2. Navigate to the Project Directory

  ```
  cd Gender-and-Age-Detection-System
  ```


### Running the Code using Jupyter Notebook


1. Open Jupyter Notebook

    • Open a terminal and run the following command

    ```
    jupyter notebook
    ```

    • Navigate to the project folder in the Jupyter Notebook dashboard and open gender_age_detection_system.ipynb.

2. Run the Notebook

    • Click on Kernel > Restart & Run All to execute the code.


### Running the Code using the Terminal


1. Navigate to the models folder of Gender-Age-Detection-System and then Right-click and click on Open in Terminal. Make sure that your terminal's path end is like this: .\Gender-and-Age-Detection-System\models>

    • Command to run .py file of Gender-Age-Detection-System
    ```
    python GenderAgeDetection.py --input ../sample_images/<ENTER_THE_NAME_OF_IMAGE>.jpg
    ```
    
    • For example, there are many sample images and we picked up narendra_modi.jpg so the command will look like this:
    ```
    python GenderAgeDetection.py --input ../sample_images/narendra_modi.jpg
    ```

    • And the output will look like this after detection of Gender and Age:

    ![sample_output](https://github.com/MeetDesaii/Gender-and-Age-Detection-System/assets/87579694/c54131c2-f619-4630-a605-ee0c919dd8e2)
