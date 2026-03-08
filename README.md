# Image Captioning with Neural Networks

# Project Overview
This project implements an **Encoder-Decoder neural network with attention** for image captioning. It uses a small subset of the Flickr8k dataset (500 images) for fast testing and demonstration. 

The main goal is to **generate captions from images** using a pre-trained model.


## Setup Instructions

1. **Clone or download the repository**  
   ```bash
   git clone https://github.com/HrayrGalstyan13/image_captioning
   cd image-captioning

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt

3. **Install model from this link and put in models folder**
   https://drive.google.com/file/d/1UwTQ3fn9TNA2A2lNr0vBWyJOH2QwT_Og/view?usp=sharing


## Notes
This project uses a small dataset (500 images) for fast testing.
Users do not need to run full training; loading the model and preprocessing images is sufficient to test captioning.
For full training, the Colab notebook provides all steps: preprocessing, feature extraction, training, and evaluation.
