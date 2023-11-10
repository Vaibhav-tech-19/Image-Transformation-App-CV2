# Image-Transformation-App-CV2

AWS Deployment Link :
http://43.205.115.76:8501/

Sreamlit Link :
https://image-transformation-app-cv2-avv2u3gt2rlz2ywvtsa5bv.streamlit.app/

## Image transformations

**1. Translation:**
Translation involves shifting an image along the x and y axes. It can be used to move the entire image to a different location. In 2D image transformations, you can specify the amount of horizontal and vertical displacement to achieve the translation.

**2. Rotation:**
Rotation is the process of rotating an image by a certain angle around a specified point. It can be used to change the orientation of an image. Common rotation angles are 90 degrees (for a 90-degree rotation) or any other angle. You can perform both clockwise and counterclockwise rotations.

**3. Scaling:**
Scaling involves resizing an image by a certain factor along the x and y axes. You can scale an image up to make it larger or down to make it smaller. Scaling by a factor greater than 1 makes the image larger, while scaling by a factor between 0 and 1 makes it smaller.

**4. Shearing :**
Shearing is a transformation that distorts the shape of an image. It involves tilting or slanting an image along one or both axes. Shearing can be applied in both horizontal and vertical directions, and it can be used to create various effects, such as making an object appear to be skewed or stretched.


## Overview
This Streamlit web application allows users to upload an image and apply various transformations, including translation, rotation, scaling, and shearing. The transformations are applied interactively using sliders, providing a visual representation of the effects on the uploaded image.

## Features
- **File Uploader:** Users can upload images in jpg, png, or jpeg formats.
- **Interactive Transformations:** Sliders for rotation angle, scale (X and Y), and shear (X and Y) allow users to dynamically adjust transformation parameters.
- **Apply Transformations:** Clicking the "Apply Transformations" button displays the transformed images alongside the original image with captions indicating the applied transformation.

## Usage
1. Install the required dependencies:

    ```bash
    pip install streamlit opencv-python numpy
    ```

2. Run the Streamlit app:

    ```bash
    streamlit run image_transformation.py
    ```

3. Open the provided URL in your web browser.

4. Upload an image using the file uploader.

5. Adjust the transformation parameters using the sliders.

6. Click the "Apply Transformations" button to see the results of the selected transformations.

## File Structure
- `image_transformation.py`: Main Streamlit application code.
- `requirements.txt`: List of required Python packages.

## How to Customize
- To modify the appearance or behavior of the web app, edit the `image_transformation.py` file.
- Customize the code based on your specific requirements.
- Feel free to extend the functionality or integrate additional features.

## Dependencies
- [Streamlit](https://streamlit.io/)
- [OpenCV](https://opencv.org/)
- [NumPy](https://numpy.org/)
