
---

# Face Recognition System

## Abstract

This project focuses on a face recognition system capable of distinguishing individual identities through facial features. Utilizing Convolutional Neural Networks (CNN) with TensorFlow and TFlearn, this system encompasses face detection and recognition phases. Detection identifies the presence of faces in images, while recognition attributes names to detected faces. Additionally, the project explores audio feedback using Google Text-to-Speech (gtts) to verbalize recognized names. Image processing is the primary domain of this system's application.

### Keywords

- Face Recognition System
- OpenCV
- CNN
- TensorFlow
- TFlearn
- Tkinter
- gtts

## Table of Contents

1. [Introduction]
   - Background
   - Problem Statement
   - Objectives
   - Future Scope
   - Limitation
2. [Requirement and Feasibility Analysis]
   - Literature Review
   - Requirement Analysis
   - Feasibility Study
   - Structuring System Requirements
3. [Design](#design)
   - System Architecture
   - Face Recognition Approach
4. [Implementation and Testing]
   - Tools and Libraries Used
   - Data Collection
   - CNN Recognition Algorithm
   - Testing
5. [Conclusion and Future Work]

## Introduction

### Background

The project introduces a robust face recognition system leveraging object detection techniques and deep learning for accurate identification. Employing libraries such as TensorFlow, TFlearn, and OpenCV, it aims to create a dataset for recognition and detect faces with high accuracy.

### Problem Statement

Traditional security measures like locks and passwords are prone to breaches and loss. This project proposes a face recognition system as a more secure and efficient alternative.

### Objectives

- Detect faces in images.
- Match and recognize faces with previously captured images.
- Provide accurate identification, such as names.

### Future Scope

Future enhancements include adding scanner support and improving recognition under varying conditions.

### Limitation

Challenges include insufficient lighting, obstructions like sunglasses or hair, and distinguishing between identical twins.

## Requirement and Feasibility Analysis

### Literature Review

Traces the evolution of face recognition technology from the 1960s, highlighting significant milestones like the development of Eigenfaces and the Viola-Jones detection algorithm.

### Requirement Analysis

Details the project's functional, non-functional, and technical requirements, including software and hardware specifications.

### Feasibility Study

Assesses the technical, economic, and operational feasibility, confirming the project's viability.

## Design

Outlines the system's architecture, emphasizing the face detection and recognition process. Utilizes the Haar-Like algorithm for detection and neural networks for recognition.

## Implementation and Testing

### Tools and Libraries Used

- **OpenCV:** For image processing and face detection.
- **TensorFlow and TFlearn:** For training the recognition model.
- **Jupyter Notebook:** As an IDE for code development and testing.

### Data Collection

Utilizes OpenCV for collecting and processing image data to create a dataset for training.

### CNN Recognition Algorithm

Explains the CNN architecture, including convolutional, pooling, ReLU, and fully connected layers, for face recognition.

### Testing

Covers integration and system testing to ensure the project's functionality and performance.

## Conclusion and Future Work

Concludes that the system achieves its objective of recognizing faces accurately. Future work will focus on distinguishing between look-alikes and improving recognition with minimal data and under challenging conditions.

