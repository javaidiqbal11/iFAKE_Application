<!-- Adding a GIF after main title -->

<h1 align="center">iFAKE - Image/Video Forgery Detection Application</h1>

This repository contains two main folders:

1. **iFAKE_AI** - This folder contains the AI Jupyter notebook files used to create the proposed CNN model for forgery detection and classification. The notebook files demonstrate the process of training and testing the model on the FIDAC & CASIA dataset.

2. **iFAKE_WebApp** - This folder contains the web application project. The web application is built on the Django framework and provides a user-friendly interface for detecting image and video forgeries.


## Pre-trained Models

We provide links to download our pre-trained models for image & video forgery detection and classification:

- [Image Model weigths](https://drive.google.com/drive/folders/1B4ODeK_QQ6XMFo6i6EEup1nZC6PllVfu?usp=sharing)
- [Video Model weigths](https://drive.google.com/drive/folders/1irYZbRnr4Y7jKieSyhjxHxwk43oSMqh-?usp=sharing)

## Running the Web Application

To run the web application on Windows, Linux, or Mac, follow these steps:

1. Install Python3 and pip3
2. Clone this repository
3. Open a terminal and navigate to the IFAKE_WebApp folder
4. Run the following command to install the required Python packages:

    ```
    pip3 install -r requirements.txt
    ```

5. Run the following command to start the web application:

    ```
    python manage.py runserver
    ```

6. Open a web browser and go to http://127.0.0.1:8000/ to access the web application.

## Screenshots
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/index.JPG" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/imageDetection1.png" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/imageDetection2.png" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/metadata.JPG" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/videoDetection.png" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/pdfDetection.png" alt="Image description" width="60%">




The screenshots show different features of our web application, including the image and video forgery detection functionality, and the ability to upload and view results of detected forgeries.


