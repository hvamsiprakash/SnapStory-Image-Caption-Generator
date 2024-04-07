# SnapStory: Image Caption Generator

SnapStory is an image caption generator tool that automatically generates captions for uploaded images. Leveraging the Flickr dataset, where each image is paired with five captions, the model produces descriptive and engaging descriptions of the images. Explore the fascinating world of image captioning with SnapStory!

## Features

- **Image Caption Generation:** Automatically generates captions for uploaded images.
- **Flickr Dataset Utilization:** Trained on the Flickr dataset, ensuring diverse and descriptive captions.
- **LSTM Model:** Employs a Long Short-Term Memory neural network architecture for effective caption generation.
- **Supports Various Image Formats:** Accepts images in JPG, JPEG, and PNG formats.

## How it Works

1. **Upload Image:** Choose an image from your device to generate a caption.
2. **Caption Generation:** The uploaded image is processed, and its features are extracted using the MobileNetV2 model. The LSTM model then generates a caption for the image.
3. **Display Caption:** The generated caption is displayed alongside the uploaded image.

## Limitations

While SnapStory is highly effective in generating captions for images from the Flickr dataset, it may occasionally produce inaccurate results for new or uncommon images.

## Dataset

The model is trained on the Flickr8k dataset, available on [Kaggle](https://www.kaggle.com/datasets/hsankesara/flickr-image-dataset). This dataset comprises over 8,000 images, each paired with five captions.

## Try it Out!

Experience SnapStory in action by visiting the [SnapStory Web App](https://image-captioning-kfzycvwflqjwyuiplgylnh.streamlit.app/)!




