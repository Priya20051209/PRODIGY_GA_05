# Neural Style Transfer in Google Colab

This project demonstrates **Neural Style Transfer** using **TensorFlow** and **Keras** in Google Colab. It combines the **content** of one image with the **style** of another to create a unique stylized image.

---

##  Project Structure

Neural-Style-Transfer/
│
├── content.jpg # Your content image
├── style.jpg # Your style image
├── output/ # Folder for generated images
└── README.md

---

##  Prerequisites

This notebook uses **Google Colab**, which comes pre-installed with most required libraries. However, you need to install TensorFlow if not available:

```python
!pip install tensorflow
import tensorflow as tf
import numpy as np
import matplotlib.pyplot as plt
from PIL import Image
 How to Run

Open the notebook in Google Colab
.

Upload your content and style images.

Run all cells in order:

Load and preprocess images.

Load pre-trained VGG19 model.

Extract style and content features.

Perform style transfer optimization.

Save and display the final stylized image.

The output image will be saved in the output/ folder.
