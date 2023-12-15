# Intrusion Detection System with KDD Cup 1999 Dataset

## Overview

This repository contains the code and resources for an Intrusion Detection System (IDS) utilizing the KDD Cup 1999 dataset. The system incorporates feature selection techniques and employs both stacking and voting classifiers for enhanced accuracy and robustness.

## Features

- **KDD Cup 1999 Dataset:** The system is built on the widely used KDD Cup 1999 dataset, providing a comprehensive set of network traffic data for training and testing.

- **Feature Selection:** To optimize model performance, feature selection techniques have been applied to identify and utilize the most relevant features, reducing dimensionality and enhancing efficiency.

- **Stacking Classifier:** The system implements a stacking classifier, combining the strengths of multiple base classifiers to improve overall predictive performance. This ensemble approach enhances the model's ability to capture complex patterns in the dataset.

- **Voting Classifier:** A voting classifier is employed to aggregate the predictions of multiple individual classifiers, promoting a democratic decision-making process. This helps to mitigate individual model biases and achieve more robust results.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/intrusion-detection-system.git
   cd intrusion-detection-system
