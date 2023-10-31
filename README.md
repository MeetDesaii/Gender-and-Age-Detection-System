# Gender-and-Age-Detection-System

### Introduction

- This project aims to accurately detect the gender and age of individuals using machine learning models. It is implemented in Jupyter Notebook and primarily uses Python for the backend logic.


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
