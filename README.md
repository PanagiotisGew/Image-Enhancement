Image Enhancement App
Authors: Georgiadis Panagiotis & Bletsas Apostolos.

This is a simple web application built using Streamlit and OpenCV that allows users to enhance and transform images. The app provides several image processing options, including blur filters, contrast adjustment, brightness adjustment, color balance, grayscale enhancement, and even cartoonization.

Features
1) Input Modes: You can upload an image file (in formats like PNG or JPG) or use your computer's camera to capture a new image.
2) Blur Filters: Apply various blur filters, including Averaging and Bilateral.
3) Image Enhancement: Adjust image contrast, brightness, and color balance. You can also choose to enhance grayscale images.
4) Cartoonization: Add a cartoon effect to your images.
5) Encoding Options: Choose to save the processed image as PNG or JPEG, with adjustable JPEG quality.
6) Download Processed and Original Images: Download the processed image with a chosen format and the original image as well.


How to Use: 

Clone or download the repository to your local machine.

Make sure you have the necessary libraries installed. You can install them using pip:

Copy code:
``
pip install streamlit opencv-python-headless numpy
``
Run the app by navigating to the project directory and running the following command:

Copy code
``
streamlit run app.py
``
The app will open in your web browser. You can upload an image or use your camera to capture one.

Adjust the image processing options using the sidebar controls.

Click the "Download Processed" button to save the enhanced image.


Dependencies:

Streamlit: For building the web interface.
OpenCV: For image processing and manipulation.
NumPy: For numerical operations.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to the Streamlit and OpenCV communities for their excellent documentation and resources.
Feel free to modify this README to include any additional information, such as troubleshooting tips or additional acknowledgments. Good luck with your GitHub repository!
