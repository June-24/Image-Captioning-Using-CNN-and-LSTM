# Image Captioning using CNN and LSTM

This project implements an image captioning model using a Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) network, trained on the Flickr dataset. The model generates descriptive captions for images by learning the correlation between visual features and text.

## Overview

Image captioning combines computer vision and natural language processing to generate meaningful descriptions of images. Our model uses:

- **CNN** for feature extraction from images.
- **LSTM** for generating coherent sentences based on visual features.

The model is trained on the Flickr dataset, which contains thousands of images and corresponding captions.

## Model Architecture

1. **CNN**: Pre-trained CNN (DenseNet201) to extract high-level image features.
2. **LSTM**: A sequential LSTM network to generate captions based on the extracted features.

## Dataset

We used the **Flickr8k** dataset, containing:
- 8,000 images with five captions per image.
- Images span diverse subjects, providing a robust base for caption generation.

## Results

Our model generates captions that capture the main objects and activities in the images, showcasing reasonable understanding despite dataset limitations.

## Deployment

The model is deployed as a web application on **Streamlit**. You can try the app here: [Caption Crafter](https://caption-crafter.streamlit.app/).

## Future Improvements

- Use larger datasets, such as Flickr30k or MS COCO.
- Experiment with transformer-based models for better performance.

## Demo

Visit the deployed application: [Caption Crafter](https://caption-crafter.streamlit.app/)

