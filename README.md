# Autism Spectrum Disorder Detection Using VGG16 and VGG19

This project utilizes Convolutional Neural Networks (CNNs), specifically VGG16 and VGG19 architectures, to detect Autism Spectrum Disorder (ASD) from facial images.

## Table of Contents

- [Introduction](#introduction)
- [Problem Definition](#problem-definition)
- [Existing System](#existing-system)
  - [Visualization of Eye-Tracking Patterns in ASD](#visualization-of-eye-tracking-patterns-in-asd)
  - [Facial Expression Recognition with Improved VGG CNN](#facial-expression-recognition-with-improved-vgg-cnn)
  - [Multi-Scale Dynamic Graph Learning for Brain Disorder Detection](#multi-scale-dynamic-graph-learning-for-brain-disorder-detection)
  - [Evaluating EEG and Eye Movements for ASD](#evaluating-eeg-and-eye-movements-for-asd)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

Autism Spectrum Disorder (ASD) is a complex developmental disorder characterized by challenges with social interaction, communication, and restrictive/repetitive behaviors. Early screening and diagnosis are critical, yet current methods rely on time-intensive clinical observations by specialized experts. There is a need for automated tools to help identify children at risk for ASD. Recent research suggests facial image analysis using deep convolutional neural networks (CNNs) could enable accurate and accessible screening.

## Problem Definition

The objective of this project is to develop a robust and accurate system that can identify potential indicators of ASD in pediatric images using deep learning architectures, specifically VGG16 and VGG19. Early diagnosis of ASD is crucial for timely intervention and support, making the exploration of advanced image analysis techniques a compelling avenue.

## Existing System

### Visualization of Eye-Tracking Patterns in ASD

Eye-tracking technology has become instrumental in studying neurodevelopmental disorders, including ASD, by providing insights into gaze patterns and fixation points during various tasks. Visualizing eye-tracking patterns in individuals with ASD can potentially uncover distinct differences in visual processing and attentional mechanisms compared to neurotypical individuals.

### Facial Expression Recognition with Improved VGG CNN

Facial expression recognition is valuable in various applications, including emotion analysis and human-computer interaction. The use of an improved VGG Convolutional Neural Network (CNN) indicates a refinement of the original VGG architecture to enhance the network's performance specifically for facial expression recognition.

### Multi-Scale Dynamic Graph Learning for Brain Disorder Detection

Functional MRI provides insights into brain activity and connectivity. The "Multi-Scale Dynamic Graph Learning" approach addresses the dynamic changes in brain connectivity patterns across different scales, which is crucial for understanding brain disorders like ASD.

### Evaluating EEG and Eye Movements for ASD

This interdisciplinary approach combines EEG and eye movement analyses to gain insights into the neurobiological and behavioral aspects associated with ASD. Integrating these modalities allows for a comprehensive understanding of the neurobehavioral characteristics associated with ASD.

## Repository Structure

- `data/`: Contains raw and processed data.
- `notebooks/`: Jupyter notebooks for data exploration and analysis.
- `src/`: Source code for data preprocessing, model definition, training, and evaluation.
- `models/`: Directory for saving trained models.
- `docs/`: Project documentation and reports.
- `tests/`: Unit tests for the project's codebase.

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/ASD-Facial-Image-Detection.git
cd ASD-Facial-Image-Detection
pip install -r requirements.txt
