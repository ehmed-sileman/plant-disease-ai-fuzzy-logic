# Plant Disease Detection and Treatment Tracking Using AI and Fuzzy Logic

Graduation project in Artificial Intelligence developed as part of a student team at the Faculty of Informatics Engineering, Damascus University.

**Project Contributor:** Ehmed Silêman  
**Specialization:** Artificial Intelligence

## Project Overview

This project presents an intelligent system for diagnosing plant diseases
by analyzing images of plant leaves.

The system is designed to help users identify plant diseases, provide
treatment recommendations and preventive guidance, and support treatment
follow-up using Fuzzy Logic.

## How the System Works

The system follows a multi-stage diagnosis process:

1. The user provides:
   - A plant leaf image
   - The plant name
   - Geographic location

2. A first classifier verifies whether the uploaded leaf belongs to the
   plant selected by the user.

3. If the plant type is confirmed, a second classifier analyzes the image
   using disease classes associated with that specific plant type.

4. The system provides:
   - The probable disease
   - Suggested treatment
   - Recommended active substances
   - Preventive guidance

5. Fuzzy Logic is used as part of the treatment follow-up and
   decision-support process.

## Artificial Intelligence

The project uses Artificial Intelligence and Computer Vision techniques
to analyze plant leaf images and identify diseases.

The system architecture includes concepts such as:

- Convolutional Neural Networks (CNN)
- Transfer Learning
- Image Classification
- Feature Extraction
- Object Detection
- Semantic Segmentation
- Softmax Classification

## Dual-Stage Classification

One of the main concepts of the project is a two-stage classification approach.

The first classifier verifies the plant type.

The second classifier performs disease classification using only the disease
classes associated with the verified plant type.

This approach helps reduce classification ambiguity and improve diagnosis accuracy.

## Fuzzy Logic

Fuzzy Logic is integrated into the treatment follow-up process.

Instead of relying only on fixed binary rules, the fuzzy system can evaluate
multiple treatment-related conditions and support treatment decisions based
on fuzzy rules.

## Geographic Disease Analysis

The application can use the user's geographic location to identify diseases
that are commonly reported in the surrounding area.

This feature can help users take preventive measures based on local disease patterns.

## Main Features

- Plant leaf image analysis
- Plant type verification
- AI-based disease classification
- Dual-stage classification
- Treatment recommendations
- Treatment tracking using Fuzzy Logic
- Preventive guidance
- Geographic disease analysis
- Disease and treatment information

## Technologies and Technical Areas

- Artificial Intelligence
- Machine Learning
- Deep Learning
- Computer Vision
- CNN
- Fuzzy Logic
- Image Classification
- OpenCV
- Python
- Flutter
- Django API
- Node.js
- NoSQL Databases
- GPS / Geographic Information

## Academic Field

- Artificial Intelligence
- Machine Learning
- Computer Vision
- Fuzzy Logic
- Software Engineering

## Project Contribution

**Ehmed Silêman**

Informatics Engineer — Artificial Intelligence

Website: https://ehmed-sileman.github.io/

GitHub: https://github.com/ehmed-sileman
