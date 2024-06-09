# BioImage Model Zoo Uploathon

## Overview

The BioImage Model Zoo Uploathon is an event aimed at bringing together experts and non-experts to upload models to the [BioImage Model Zoo](https://bioimage.io). Participants will engage in activities such as uploading their trained models, converting popular community models, and fine-tuning existing models. The goal is to increase the number of available models in the BioImage Model Zoo and to evaluate the process of model uploading, conversion, and fine-tuning.

## Model Categories
> Add the type of data you think it's useful to have here gathered such as the dataset it was trained on or something similar.

### 1. Models from Participants

These are models that participants, particularly those from the Human Technopole in Milan, have trained themselves.

#### Custom Models

- **µSplit: image decomposition for fluorescence microscopy**
  - **Description:** [µSplit blog post](https://ashesh-0.github.io/uSplit/)
  - **Trained By:** Ashesh (Juglab's PhD Student)
  
- **DeepContrast**
  - **Description:** [DeepContrast](https://arxiv.org/abs/2308.08365): Deep Tissue Contrast Enhancement using Synthetic Data Degradations and OOD Model Predictions.
  - **Trained By:** Nuno (Juglab's graduated PhD Student)

#### OpenCall Models
- **Model 1: Cellpose**
    - **Description:** Murine Skeletal Muscle Cell Segmentation.
    - **Meta-data:** [project git repo](https://github.com/ai4life-opencalls/oc-1-project-6/tree/main)
      
- **Model 2: Cellpose**
    - **Description:** Segmentation of Epithelial Cells.
    - **Meta-data:** [project git repo](https://github.com/ai4life-opencalls/oc-1-project-11/tree/main)

### 2. Community Interest Models

These are models identified as beneficial for the community but require additional effort to upload due to metadata and format requirements.

- **CellPose Models**
  - **Description:** Pre-trained Cellpose models popular in the community.
  
- **Segment Anything Model (SAM)**
  - **Description:** SAM model conversion being worked on by Constantine.

### 3. Fine-tuned Models

These models will be fine-tuned by non-experts during the event, using tools like ZeroCostDL4Mic notebooks. A competition will be held to determine the best models to upload based on performance and user experience.

- **Instance Segmentation for HeLa Cells**
  - **Description:** Participants will download, fine-tune, and export models.
  - **Base Model:** [Affable Shark Model](https://bioimage.io/#/?tags=affable-shark&id=10.5281%2Fzenodo.5764892)
  - **Training Data:** Modified dataset from the [Cell Tracking Challenge](https://celltrackingchallenge.net/2d-datasets/), [download here](YOUR_GOOGLE_DRIVE_LINK)
  
## Progress Tracking Table

| Model Name                                    | Category                  | Description                                                        | Status      | Meta-data Complete | Exported | Uploaded | Notes                    |
|-----------------------------------------------|---------------------------|--------------------------------------------------------------------|-------------|--------------------|----------|----------|--------------------------|
| µSplit: image decomposition for fluorescence microscopy | Participant Models        | Microscopic image splitting                                        | Not Started | No                 | No       | No       |                          |
| DeepContrast                                  | Participant Models        | Deep Tissue Contrast Enhancement using Synthetic Data Degradations and OOD Model Predictions | Not Started | No                 | No       | No       |                          |
| OpenCall Cellpose Model 1                     | Participant Models        | Murine Skeletal Muscle Cell Segmentation                           | Not Started | No                 | No       | No       |                          |
| OpenCall Cellpose Model 2                     | Participant Models        | Segmentation of Epithelial Cells                                   | Not Started | No                 | No       | No       |                          |
| CellPose Models                               | Community Interest Models | Pre-trained Cellpose models popular in the community               | Not Started | No                 | No       | No       |                          |
| Segment Anything Model (SAM)                  | Community Interest Models | SAM model conversion by Constantine                                | In Progress | No                 | No       | No       |                          |
| Instance Segmentation for HeLa Cells          | Fine-tuned Models         | Participants will fine-tune the Affable Shark model using a modified dataset from the Cell Tracking Challenge | Not Started | No                 | No       | No       | Download dataset from [here](YOUR_GOOGLE_DRIVE_LINK) |
