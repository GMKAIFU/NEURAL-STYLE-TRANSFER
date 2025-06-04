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

This project demonstrates the implementation of a Neural Style Transfer (NST) model using TensorFlow and TensorFlow Hub to apply artistic styles to user-supplied photographs. The objective is to automate the generation of stylized images by blending the content of one image (such as a user’s photo) with the artistic style of another image (such as a painting), creating stunning visual effects.

Neural Style Transfer is a deep learning technique that merges two images: a content image and a style image. It uses a convolutional neural network (CNN) to extract the content features from the content image and style features from the style image, and then combines them to produce a stylized output. This is achieved using a pre-trained neural network, making it highly efficient and ideal for real-time applications.

In this project, I used the Magenta Arbitrary Image Stylization Model v1-256, which is available on TensorFlow Hub. This model is specifically designed for fast and high-quality style transfer and eliminates the need to train a neural network from scratch. The model accepts two input tensors: one for content and another for style. It outputs a single stylized image that represents the content of the first input in the style of the second.

The Python script is written to be user-friendly, automated, and scalable. It automatically reads all content images from a folder named content_images/ and all style images from style_images/. The script then applies each style image to every content image, generating multiple stylized outputs. For instance, if the user provides 4 photos and 3 style paintings, the script will automatically generate 12 stylized outputs—one for each combination.

The output images are saved in a folder named stylized_outputs/, with clear filenames following the format:
contentname_styled_with_stylename.jpg, ensuring easy identification and organization of results.

The script relies on the following Python libraries:

tensorflow and tensorflow_hub – for loading and using the pre-trained model.

numpy – for array manipulation.

Pillow (PIL) – for image loading, resizing, and saving.

In addition, the script includes error handling to ensure that only valid images are processed and that any issues during file reading or model execution are clearly reported.

This project is a powerful demonstration of how AI can be applied creatively in real-world tasks. By integrating a powerful pre-trained model, the system allows users to experiment with art and AI without needing extensive technical knowledge. It showcases my skills in deep learning, image processing, automation, and software integration. This system could be extended into mobile applications, online tools, or creative platforms where users can upload their own photos and apply famous painting styles instantly.

_How the Code Works_

The Python script starts by importing the required libraries. It then loads the Magenta Arbitrary Image Stylization model from TensorFlow Hub. Two folders—content_images/ and style_images/—are scanned for image files. Each image is read, resized, and converted to a format suitable for the model using TensorFlow’s preprocessing utilities.

For every content-style pair, the model processes both images and outputs a new stylized image tensor. This tensor is then converted back to a standard image format using NumPy and PIL, and saved in a stylized_outputs/ directory with a clearly named filename.

The code is optimized to loop through all combinations of content and style images without user interaction, enabling batch processing. Any errors encountered (e.g., unreadable images or model failures) are caught and reported cleanly, preventing the script from crashing midway. This makes the code robust and reliable for larger datasets or integration into larger applications.




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

# RUNNING OUTPUT FROM VSCODE
![Image](https://github.com/user-attachments/assets/10650296-427c-4bfb-b4ea-0df48cd7167e)

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
