# Face Recognition Using VGGFace

This project demonstrates face recognition using the VGGFace model and OpenCV. It can recognize and identify faces in images and video streams. The project is divided into several sections, each with its own purpose and functionality.

## Table of Contents

1. [Face Extraction](#1-face-extraction)
2. [VGGFace Model](#2-vggface-model)
3. [Face Recognition](#3-face-recognition)
4. [Testing on a Video](#4-testing-on-a-video)

## 1. Face Extraction

In this section, the project extracts faces from images of people. You are required to place photos of people with a visible face in the "people" folder. The code uses the `haarcascade_frontalface_default` detector model to extract faces and places the extracted faces in the "group_of_faces" folder. This step is essential for creating a database of faces to recognize.

## 2. VGGFace Model

This section defines the VGGFace model, loads the pre-trained weights, and prepares the model for face recognition. The VGGFace model is a deep learning model for face recognition and is used for feature extraction from faces.

## 3. Face Recognition

In this part, the project uses the VGGFace model and the faces extracted earlier to recognize and identify faces in real-time using a webcam. It calculates the similarity (Cosine Similarity) between the captured face and the faces in the database and displays the recognized person's name if a match is found.

## 4. Testing on a Video

The final section demonstrates how to test the face recognition model on a video. Faces are extracted from images placed in the "friends" folder and used as reference faces. The project then runs the face recognition model on a test video, identifying and labeling recognized faces.

This project provides a comprehensive solution for face recognition using deep learning and is a valuable resource for anyone interested in implementing face recognition systems.

### How to Use

To use this project, follow these steps:

1. Place photos of people in the "people" folder.
2. Replace the default image "Rajeev.jpg" with your face for testing.
3. Run the code to extract faces, load the VGGFace model, and perform face recognition.
4. You can also extract faces from images in the "friends" folder and test the model on a video by following the provided instructions.
5. Make sure to download the pre-trained weights for the VGGFace model and place them in the project directory called as vgg_face_weights.h5.
6. If you are using Apple silicon chips, install anaconda and create new environment using the environment.\_mlpyml file provided in the repository.

For more details and the code, refer to the Jupyter Notebook provided in this repository.
