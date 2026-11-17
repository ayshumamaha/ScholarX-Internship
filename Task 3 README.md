# Image Prediction API Using Python and Flask

## 1. Project Overview

The Image Prediction API is a Python application that accepts uploaded images and predicts their dominant-colour category. It uses image processing techniques to extract RGB features and a simple nearest-neighbour classifier to make predictions.

The application is developed using Flask and returns prediction results in JSON format.

## 2. Objectives

- Develop an image prediction API using Python.
- Understand basic image processing.
- Extract RGB features from images.
- Train a simple image classifier.
- Accept image uploads through an API.
- Return prediction results in JSON format.

## 3. Tools & Technologies Used

- **Programming Language:** Python
- **Framework:** Flask
- **Libraries:** Pillow, NumPy
- **Concepts:** Image Processing and Machine Learning
- **Response Format:** JSON
- **Editor:** VS Code / Python IDLE

## 4. Features Implemented

- **Sample Dataset:** Generates sample images automatically.
- **Image Upload:** Accepts images through an API endpoint.
- **Feature Extraction:** Calculates average RGB values.
- **Model Training:** Trains a simple nearest-neighbour classifier.
- **Image Prediction:** Predicts Red, Green, or Blue.
- **JSON Response:** Returns the prediction as API output.
- **Error Handling:** Handles missing and invalid image uploads.

## 5. Application Workflow

1. Start the Flask API.
2. Generate sample training images.
3. Extract image features.
4. Train the classifier.
5. Upload an image through the API.
6. Process the uploaded image.
7. Predict its category.
8. Return the result in JSON format.

## 6. How to Run the Project

1. Install Python.
2. Install the required libraries:

   `pip install flask pillow numpy`

3. Save the code as `image_api.py`.
4. Run the application:

   `python image_api.py`

5. Open `http://127.0.0.1:5000` in your browser to view the API information.
6. Send an image to the `/predict` endpoint using an API testing tool or the provided test instructions.

## 7. Expected Output

The API accepts an image and returns a JSON response containing the predicted dominant-colour category. The supported categories are Red, Green, and Blue.

## Author
M. Ayshwarya

## 8. Conclusion

The Image Prediction API demonstrates the use of Python, image processing, and Flask for building an image classification service. It provides practical experience in extracting image features, training a basic classifier, accepting image uploads, and returning predictions through an API.
