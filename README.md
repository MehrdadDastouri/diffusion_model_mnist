# Diffusion Model for Image Generation on MNIST

"This project implements a diffusion-based generative model using a U-Net architecture to generate images. The model is trained on the MNIST dataset and learns to reverse a fixed noise diffusion process."

Features:
  - Implements a noise diffusion process with a linear beta schedule.
  - Uses a U-Net architecture to predict noise added to images at various timesteps.
  - Trains the model on the MNIST dataset to generate realistic grayscale digits.
  - Saves generated images at specific training intervals (e.g., every 10 epochs).
  - Visualizes the final generated images.
