# Pedestrian-Intent-Detection

Collaboration capstone project with custom dataset for predicting the trajectory and intention behind a pedestrian's actions.

Team: @ vedika1102, @ tanishqtodkar, @ shubhpareek


  ![Main_output_1 (1)](https://github.com/Vedika1102/Pedestrian-Intent-Detection/assets/88620694/3238a5c9-81f2-479e-8726-b079e7b0137c)


# Aim/ Objective:

The system aims to detect the presence of pedestrians, their movement patterns and predict their intentions such as crossing the street or standing on the sidewalk

# System Block Diagram:
<img width="430" alt="Screenshot 2023-12-21 170132" src="https://github.com/Vedika1102/Pedestrian-Intent-Detection/assets/88620694/d1d55410-22ca-4d95-ac67-937c0fa8a6d2">


# Dataset

The custom dataset created for pedestrian intent detection in an Indian scenario is specifically designed to address the unique challenges posed by pedestrian
behavior in Indian roads. The dataset is based on a large number of raw videos recorded using the FitSpark Eagle i9 Plus camera, which has a wide field of view and high resolution. These videos were then processed and cleaned using the Roboflow platform, which is a powerful tool for data annotation and preparation. The platform enables easy and accurate labeling of objects in images and videos, which is crucial for training machine learning models.

In the custom dataset, four different classes were used for pedestrian intent detection. 

* person facing right
* person facing left
* person facing towards
* person facing away

These classes were chosen based on the observation that pedestrians in Indian roads generally exhibit these four types of behavior. By limiting the dataset to only four classes, the model training process can be streamlined and optimized, making it easier to develop a reliable and accurate pedestrian intent detection system.


