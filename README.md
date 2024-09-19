# Sar_images_to_rgb
SAR Image to RGB Image Colorization
This project focuses on developing a deep learning model to accurately colorize grayscale Synthetic Aperture Radar (SAR) images, enhancing feature interpretation and analysis for remote sensing applications.

# Problem Statement
Colorizing SAR images helps in visualizing and interpreting data more effectively, making it easier to identify and analyze features for remote sensing tasks.

# Solution
Model Architecture: Used U-Net architecture to accurately colorize SAR images, capturing fine structural and textural details for precise color reconstruction.
Interpretability: Improved interpretability and usability of SAR data in remote sensing applications.
Advantages
Enhanced Visualization: Clearer and more detailed images for improved feature recognition.
Improved Data Analysis: Simplifies interpretation of large datasets, aiding faster decision-making.
Increased Classification Accuracy: Enables better terrain differentiation for precise classification.
Adaptability: Easily applicable to other image translation tasks.
Workflow

#Preprocessing:
EuroSAT color images are converted to grayscale using OpenCV.
Images are resized to (64x64) and normalized for model input.
Model:

Architecture: U-Net is used for image colorization, with an encoder to extract features and a decoder to reconstruct RGB images.
Training: The model is trained using Mean Squared Error (MSE) loss and Adam optimizer on the training dataset.
Evaluation:

Performance is validated by comparing grayscale inputs with predicted colorized outputs.
# Datasets
EuroSAT Dataset: https://ec.europa.eu/eurostat/data/database
EuroSAT Grayscale: Custom preprocessing script to convert color images to grayscale.
# Tools & Libraries
TensorFlow
OpenCV
# Acknowledgements
Thanks to the EuroSAT team for providing the dataset.
