# NEURAL STYLE TRANSFER

---

**COMPANY:**  CODTECH IT SOLUTIONS  
**NAME:**  G M KAIFU  
**INTERN ID:**  CT06DN1863  
**DOMAIN:**  ARTIFICIAL INTELLIGENCE  
**DURATION:**  6 WEEKS  
**MENTOR:**  NEELA SANTOSH

---

## 📌 PROJECT TITLE  
**Implement a Neural Style Transfer Model to Apply Artistic Styles to Photographs**

---

##  DESCRIPTION

This project focuses on implementing a Neural Style Transfer (NST) model using TensorFlow and TensorFlow Hub to apply various artistic styles to user-supplied photographs. The goal is to develop a working Python script that takes one or more content images (photographs) and applies multiple artistic styles (like famous paintings) to generate stylized outputs automatically.

The technique of Neural Style Transfer involves deep learning, where the model extracts the content from one image and the style from another image and blends them together. In this project, I used the pre-trained Magenta Arbitrary Image Stylization Model v1-256, available on TensorFlow Hub. This eliminates the need for training a model from scratch and allows real-time stylization of images with high visual quality.

The Python script is designed to be user-friendly and scalable. It reads all the content images from a folder named content_images and style images from another folder style_images. For each combination of content and style, the model generates a stylized output and saves it into the stylized_outputs folder. This means that if there are 3 photos and 3 styles, the script will produce 9 outputs automatically.

Required libraries include tensorflow, tensorflow_hub, numpy, and Pillow (PIL). The code ensures proper error handling, image preprocessing, and result saving. All outputs are named clearly using the format of photo_styled_with_style.jpg.

This project not only demonstrates my understanding of deep learning and image processing but also shows my ability to integrate pre-trained AI models into real-world tasks. It is an ideal example of applying AI creatively for artistic and practical uses.


---

##  TOOLS USED  

- **Python 3.7+**
 
- **TensorFlow 2.x**
    
- **TensorFlow Hub**
   
- **NumPy**
  
- **Pillow (PIL)**
  
- **Google Magenta’s Style Transfer Model**

---

##  REQUIRED PYTHON MODULES

Install all modules using pip:

pip install tensorflow tensorflow-hub pillow numpy

tensorflow>=2.0.0

tensorflow-hub

pillow

numpy


# Important Module Links:

📦 TensorFlow
https://www.tensorflow.org/install

📦 TensorFlow Hub
https://www.tensorflow.org/hub

🖼️ Pre-trained Style Transfer Model
https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2

🧠 Magenta Project (by Google Brain):
https://magenta.tensorflow.org/

# Sample Artistic Style Images:

These are the sample style images used:

Starry Night: starry.png

Wave: wave.jpg

Mosaic: mosaic.jpg

You can download your own artistic styles or use copyright-free artworks.


# How It Works

Load a content image (like a selfie or photo).

Load a style image (like a painting).

Feed both images into a pre-trained model from TensorFlow Hub.

The model outputs a new image that looks like the photo painted in the style.

This is repeated for all content-style combinations automatically.

_OUTPUT SAVED_

Saved automatically inside the stylized_outputs folder.

Named like: output1.jpg, output2.jpg, output3.jpg, etc.

Ready to use in reports, presentations, or as portfolio projects.

## OUTPUTS

# OUTPUT-1

![Image](https://github.com/user-attachments/assets/fca7ddcf-9c96-4492-ba73-3842a5055a35)

# OUTPUT-2

![Image](https://github.com/user-attachments/assets/b09f0314-1b4a-4aba-bd06-700dd2e715d3)

# OUTPUT-3

![Image](https://github.com/user-attachments/assets/e4236be6-dbe4-403a-8d9e-90c33996b03a)

# OUTPUT-4

![Image](https://github.com/user-attachments/assets/2d940e7f-7c24-4c11-9878-784ec105c9b8)

# OUTPUT-5

![Image](https://github.com/user-attachments/assets/9b5cc1fc-4278-4c51-82b2-b11676da5780)

# OUTPUT-6
![Image](https://github.com/user-attachments/assets/01445141-ec46-4ab0-b642-33956977e695)
