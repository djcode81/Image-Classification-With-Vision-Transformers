# Vision Transformer Project

This project explores the capabilities of **Vision Transformers** (ViTs) through various tasks, including **simple image classification**, **zero-shot image classification**, and **zero-shot object detection**. The project demonstrates how ViTs can be used to classify images and detect objects in scenarios where traditional training data may be limited.

## Project Overview

This project showcases the performance of Vision Transformers using pre-trained models to:
1. **Simple Image Classification**: Classify images into predefined categories using a pre-trained ViT model.
2. **Zero-Shot Image Classification**: Predict image categories that the model has not seen during training.
3. **Zero-Shot Object Detection**: Identify and localize objects within images, even if the objects have not been encountered during training.

The project was developed as a guided project with the help of DataCamp.

## Technologies Used

- **Python**: Programming language used for implementing the project.
- **PyTorch**: Framework for deep learning, used to work with Vision Transformers.
- **Transformers (Hugging Face)**: Library to access pre-trained Vision Transformer models.
- **Matplotlib**: For data visualization and displaying images.
- **PIL (Python Imaging Library)**: For image manipulation and preprocessing.


## Project Structure

The project is organized as follows:

1. **Task 1: Simple Image Classification**
   - Loads a pre-trained `vit-base-patch16-224` model.
   - Classifies images into one of 1,000 categories.
   - Displays the predicted category for a sample image.

2. **Task 2: Zero-Shot Image Classification**
   - Uses the `clip-vit-large-patch14` model.
   - Classifies images into categories not seen during training.
   - Accepts a list of candidate labels to make predictions.

3. **Task 3: Zero-Shot Object Detection**
   - Implements the `owlvit-base-patch32` model for object detection.
   - Detects and localizes objects in an image using textual queries.
   - Visualizes detected objects with bounding boxes.

## How to Run the Project

### Prerequisites

Ensure you have the following libraries installed:
- `transformers`
- `torch`
- `matplotlib`
- `pillow`
- `requests`

Install the required libraries using:
```bash
pip install transformers torch matplotlib pillow requests
