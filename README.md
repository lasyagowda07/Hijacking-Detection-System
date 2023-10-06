# Hijacking-Detection-System

This project called HIJACKING DETECTION SYSTEM using Arduino UNO which contains weapon detection, face detection, an automatic door locking system, and a Tranquilizer gun that will neutralize a potential hijacker.

This project aims to develop a weapon detection system using OpenCV, a popular computer vision library. The system will be trained on a dataset of images and videos of weapons and non-weapons. Once trained, the system will be able to automatically detect weapons in new images and videos.

# Dataset
The dataset consists of a set of images contaning a weapon and a set of images that don't.

Cascade trainer GUI is used to train the model using the dataset of positive and negative images:
positive images: images with weapon
negative images: images without weapons

This trained model is used to detect weapons in realtime imaging using OpenCV libraries.
The data is then sent to the Hijacking detection system to drive the motors as per its need.

![weapon](https://github.com/k8wi/Hijacking-Detection-System/assets/95972832/1a68f0f6-1531-4b79-b6a2-a9ad842746a5)


![Capture](https://github.com/k8wi/Hijacking-Detection-System/assets/95972832/75c1c0e4-2b6c-49cb-af00-f918a30b2024)
