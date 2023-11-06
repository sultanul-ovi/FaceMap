<h1 align="center">
   <img src="https://github.com/sultanul-ovi/FaceMap/blob/master/images/banner.png"  width="500" height="500" />
</h1>

<h4 align="center">
ML-based Face Recognition Web Application
</h4>



## Project Overview
FaceMap is a sophisticated face recognition web application that leverages the power of machine learning and MLOps to accurately identify individuals in images and videos. It is built using Flask and deployed on Heroku, making it easily accessible over the web.

## What This Project Does
FaceMap provides a suite of features for automated face detection and recognition:

- **Face Detection**: Automatically detect faces in images and videos with high accuracy.
- **Face Recognition**: Utilize a trained machine learning model to recognize and classify faces.
- **Image Processing**: Implement image preprocessing and analysis using OpenCV.
- **Model Evaluation**: Test and evaluate the machine learning model to ensure high performance.
- **Model Tuning**: Use grid search for hyperparameter tuning to optimize the model.
- **RESTful API**: Create REST APIs in Flask for client-server communication.
- **Frontend Integration**: Render HTML, CSS, and Bootstrap in the frontend with Jinja template inheritance.

## Technical Stack

- **Python**: For backend logic and machine learning model development.
- **OpenCV**: For image processing and face detection.
- **Flask**: To create the web server and RESTful APIs.
- **Heroku**: For deploying the web application.
- **Machine Learning**: Support Vector Machines (SVM) for face recognition with a pre-trained model using Eigenfaces and PCA.
- **Bootstrap**: For responsive and modern web design.

## Features

- **Automatic Face Detection**: Identify and outline faces in any given image or video.
- **Face Recognition System**: Recognize known faces with a trained classification model.
- **Image Preprocessing**: Prepare images for recognition through various preprocessing techniques.
- **User Interface**: A clean and intuitive web interface for users to upload images and view recognition results.
- **Scalability**: Designed to efficiently handle a large number of requests and can be scaled up easily.
- **Security**: Implements best practices to ensure user data is handled securely.

## Getting Started

To use FaceMap on your local machine:

1. Clone the repository.
2. Install Python and all the necessary libraries listed in `requirements.txt`.
3. Set up your environment with the necessary API keys and configurations.
4. Run the Flask app locally to test its functionality.
5. Deploy the app to Heroku following the provided instructions.


### Disclaimer

>FaceMap is for educational and research purposes only. It is not intended for use in production without proper ethical considerations and adherence to privacy laws and regulations.
