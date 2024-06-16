
#You can run the project locally using Docker with the help of the following commands.

__Step 1:__ Build Docker Image with the help of `docker build -t image_captioning .`

__Step 2:__ Run the container using `docker run -p 8501:8501 -ti  image_captioning `

__Step 3:__ Go to http://localhost:8501 to find the Streamlit based UI


# Eye for the Blind Capstone Project

## Project Description

The "Eye for the Blind" capstone project aims to develop an assistive technology solution for visually impaired individuals. This project focuses on creating a wearable device that leverages advanced machine learning algorithms and computer vision techniques to provide real-time assistance by describing the surrounding environment, reading text, and recognizing objects.

## Technologies and Applications Used

### Machine Learning & Computer Vision
- **Convolutional Neural Networks (CNNs):**
  - Employed for object detection and recognition. CNNs are used to process images captured by the wearable device's camera and identify objects in real-time.
- **Optical Character Recognition (OCR):**
  - Implemented for text recognition, enabling the device to read printed text aloud to the user.

### Natural Language Processing (NLP)
- **Speech Synthesis:**
  - Converts recognized text and detected objects into spoken words, providing auditory feedback to the user.

### Embedded Systems
- **Raspberry Pi / Arduino:**
  - Utilized as the hardware platform for integrating sensors, camera, and processing units.

### Programming Languages and Libraries
- **Python:**
  - The primary programming language for developing the machine learning models and integrating various components.
- **TensorFlow and Keras:**
  - Used for building and training deep learning models.
- **OpenCV:**
  - A library for computer vision tasks, including image and video processing.

## Applications
- **Navigation Assistance:**
  - Helps users navigate their environment by describing objects and obstacles in their path.
- **Reading Aid:**
  - Reads aloud text from books, signs, and other printed materials.
- **Object Identification:**
  - Recognizes and names objects, such as household items, facilitating daily activities for visually impaired individuals.

## Impact
The "Eye for the Blind" project aims to significantly improve the quality of life for visually impaired individuals by enhancing their independence and ability to interact with their surroundings through innovative use of machine learning and computer vision technologies.
