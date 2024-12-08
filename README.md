## Pixelation Detection and Correction System

### Overview
This project focuses on addressing pixelation in digital images, a common issue that affects image quality. The system integrates deep learning-based **pixelation detection** and advanced **image correction** techniques to improve visual clarity. It provides a robust solution with automated detection, state-of-the-art correction, and user-friendly interaction.

---

### Problem Statement
Pixelation degrades image clarity and sharpness, significantly impacting applications like photography, digital art, and medical imaging. The challenges include:
1. Visual quality degradation.
2. Manual identification of pixelation is impractical.
3. Standard scaling methods are insufficient for correction.

---

### Demo

[![Watch Demo Video](https://img.shields.io/badge/Watch-Demo-blue)](https://github.com/Shankar10032005/PIXELATION-DETECTION-AND-CORRECTION-SYSTEM/raw/main/Demo.mp4)

---

### Proposed Solution
A two-stage system combining:
- **Pixelation Detection**: A CNN-based model classifies images as pixelated or non-pixelated.
- **Image Correction**: The ESRGAN (Enhanced Super-Resolution Generative Adversarial Network) improves image quality by reducing pixelation and enhancing details.

---

### Features
1. **Automated Pixelation Detection**  
   - Detects pixelation using a CNN-based classifier.
   - Outputs binary classification: *Pixelated* or *Non-Pixelated*.  

2. **High-Quality Image Correction**  
   - Corrects pixelated images using ESRGAN and Real-ESRGAN models.
   - Enhances image details and reduces artifacts.  

3. **User-Friendly Interface**  
   - Built with **Tkinter** for intuitive interaction.
   - Allows image upload, detection, correction, and saving of enhanced images.  

4. **Real-Time Display**  
   - Displays side-by-side comparison of original and corrected images.  

5. **Save Functionality**  
   - Enables saving corrected images locally.  

6. **Multiple Super-Resolution Techniques**  
   - Integrates ESRGAN and Real-ESRGAN for flexible image enhancement.  

---

### Technologies Used
- **GUI**: Tkinter for the interface.  
- **Image Processing**: Pillow, OpenCV.  
- **Pixelation Detection**: Keras (TensorFlow backend).  
- **Image Correction**: PyTorch (ESRGAN).  
- **Data Handling**: NumPy for preprocessing and matrix operations.  

---

### Dataset
- **Total Images**: 2,490 (1,245 pixelated, 1,245 non-pixelated).  
- **Categories**:  
  - Text, handwritten and printed materials.  
  - Birds, animals, animations, games.  
  - Portraits, landscapes, and religious symbols.  

---

### Process Flow
1. **Pixelation Detection**:  
   - Load and preprocess the image.  
   - Classify using CNN.  
2. **Image Correction**:  
   - Enhance pixelated images with ESRGAN or Real-ESRGAN.  
   - Save and display the results.  

---

### Future Enhancements
- Expand dataset diversity.
- Implement real-time image detection and correction.
- Explore additional super-resolution techniques.

