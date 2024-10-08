# Streamlit Image Classification App

This Streamlit application allows users to upload images and get predictions from the OpenCLIP model, an open-source implementation of OpenAI's CLIP model. The CLIP model, which stands for "Contrastive Language-Image Pre-training," is a state-of-the-art artificial intelligence model capable of understanding both images and text.

## Features

- **Upload images**: Users can upload images directly to the app interface.
- **Get predictions**: The app uses the OpenCLIP model to predict the class or content depicted in the uploaded image based on its visual features and any accompanying text description.

## How to Use

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Streamlit app using `streamlit run streamlit_app.py`.
4. Once the app is running, upload an image using the provided file uploader.
5. Wait for the app to process the image and display the predictions.

## About CLIP Model

The OpenCLIP model is an open-source implementation of OpenAI's CLIP model, which is a powerful AI model capable of understanding both images and text. It achieves this by training on a large dataset of image-text pairs using a technique called contrastive learning. This enables the model to learn a joint representation space where images and text are semantically similar if they describe the same concept.

For more information on the original CLIP model, you can read the [original paper](https://arxiv.org/abs/2103.00020).

The OpenCLIP implementation can be found on [GitHub](https://github.com/mlfoundations/open_clip/tree/main).

## Credits

This app was created by Isaac Bravo & Katharina Prasse. It uses the OpenCLIP model, an open-source implementation of OpenAI's CLIP model.

