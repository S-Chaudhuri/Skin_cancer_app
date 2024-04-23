# Skin Cancer Detection App Project

## Introduction
The Skin Cancer Detection App is a machine learning project aimed at assisting users in early detection of skin cancer through image analysis. The app utilizes computer vision techniques and a convolutional neural network (CNN) model based on EfficientNet B7 architecture to classify skin lesions as benign or malignant.
<div style="text-align:center">
    <img src="https://github.com/S-Chaudhuri/Skin_cancer_app/blob/main/Screenshot%202024-04-23%20093210.jpg" alt="Skin Cancer Image">
</div>
## Technologies Used
- **Computer Vision (CV):** Utilized for image preprocessing, feature extraction, and segmentation.
- **EfficientNet B7:** A state-of-the-art CNN architecture known for its efficiency and accuracy in image classification tasks.
- **Python:** Programming language used for development.
- **TensorFlow:** Deep learning framework for building and training the CNN model.
- **OpenCV:** Library for image processing and manipulation.
- **Flask:** Web framework used for building the user interface of the app.

## Project Workflow
1. **Data Collection:** Gathered a dataset consisting of images of skin lesions labeled as benign or malignant.
2. **Data Preprocessing:** Performed preprocessing tasks such as resizing, normalization, and augmentation to enhance the quality and quantity of the dataset.
3. **Model Training:** Implemented the EfficientNet B7 model and trained it using the preprocessed dataset to classify skin lesions.
4. **Model Evaluation:** Evaluated the trained model using metrics such as accuracy, precision, recall, and F1-score.
5. **App Development:** Built a web-based application using Flask to provide users with an interface to upload images for analysis.
6. **Integration:** Integrated the trained model into the app backend to perform real-time classification of uploaded images.
7. **Deployment:** Deployed the app on a web server, making it accessible to users via a web browser.

## Usage
1. **User Interface:** Users can access the app through a web browser.
2. **Upload Image:** Users can upload an image of a skin lesion to the app.
3. **Analysis:** The app will process the uploaded image using the trained model and provide a prediction on whether the lesion is benign or malignant.
4. **Result Display:** The app will display the prediction along with the confidence score.
5. **Further Actions:** Based on the prediction, users can take appropriate actions such as consulting a dermatologist for further evaluation.

## Future Enhancements
1. **Multi-Class Classification:** Extend the model to classify skin lesions into different types of skin cancer.
2. **Mobile Application:** Develop a mobile version of the app for convenient access on smartphones.
3. **Integration with Dermatologist Tools:** Integrate the app with dermatologist tools for collaborative diagnosis and treatment planning.
4. **Continuous Learning:** Implement mechanisms for the model to continuously learn from new data and improve its accuracy over time.

## Conclusion
The Skin Cancer Detection App project aims to leverage the power of computer vision and deep learning to assist in the early detection of skin cancer, thereby improving patient outcomes and reducing mortality rates associated with the disease.

