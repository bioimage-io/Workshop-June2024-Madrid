# BioImage Model Zoo Uploathon: Fine-tuning Models

## Overview

During the BioImage Model Zoo Uploathon, participants will work in groups to fine-tune pre-existing models using the [BiaPy](https://biapy.readthedocs.io/en/latest/) pipeline for 2D instance segmentation or the [ZeroCostDL4Mic Notebooks](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki). The goal is to improve the model's performance and upload the best fine-tuned model to the BioImage Model Zoo.

## Objective

The objective of this activity is to:

1. Download and prepare a training dataset.
2. Fine-tune a pre-existing model using the BiaPy pipeline.
3. Evaluate the fine-tuned model's performance.
4. Select the best-performing model for upload to the BioImage Model Zoo.

## Steps to Reproduce the Fine-tuning Process on BiaPy

### 1. Dataset Preparation

Participants will use a modified dataset derived from the [Cell Tracking Challenge](https://celltrackingchallenge.net/2d-datasets/). The dataset includes HeLa cells stably expressing H2b-GFP.

- **Download the modified dataset**: [Modified Dataset](https://drive.google.com/drive/folders/1lbqKWKpwTt4vTb1eC4-Wy1Ong3rcYJA5?usp=sharing)

### 2. Fine-tune the Model

Participants will follow these steps in the provided Google Colab notebook to fine-tune the model:

1. **Upload the Dataset**:
   - Upload the training and test images along with their corresponding instance label images to the Colab environment.

2. **Train the Model**:
   - Use the training set to train the Deep Neural Network (DNN) model provided in the notebook.
   - Monitor the training process and make necessary adjustments.

3. **Apply the Model**:
   - Apply the trained model to the test images.
   - Evaluate the segmentation results.

4. **Download the Results**:
   - Download the segmentation results to your local machine for further analysis.

### 3. Evaluation

- **Performance Metrics**:
  - Evaluate the fine-tuned models using standard metrics such as accuracy, precision, recall, and F1 score.

### 4. Selection and Upload

- **Competition**:
  - A competition will be held to determine the best model based on performance metrics and user experience.
  - The winning model will be uploaded to the BioImage Model Zoo.


## Steps to reproduce fine-tuning models with StarDist from ZeroCostDL4Mic

The important step is once you have exported a model into a deepImageJ format to run it on Fiji, you will need to add some postprocess with a macro. This macro can be found [here](https://github.com/deepimagej/imagej-macros/blob/master/StarDist2D_Post-processing.ijm).
Thank you for participating and contributing to the BioImage Model Zoo!
