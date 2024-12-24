# Kidney Cancer Detection Project

This project aims to develop an early detection system for kidney cancer by integrating multi-modal data, including:

- **Medical Imaging (CT/MRI scans):** Feature extraction using pre-trained deep learning models like ResNet.
- **Clinical Data:** Patient information and clinical attributes provided in a structured Excel file.
- **Genomic Data (Optional):** Placeholder for future integration to enhance prediction accuracy.

## Key Features

### CT Scan Image Processing:
- Feature extraction using deep learning techniques.
- Dimensionality reduction with PCA for visualization and analysis.

### Data Integration:
- Combining imaging and clinical data for comprehensive analysis.

### Goal:
- Early and accurate diagnosis to improve patient outcomes.

## Folder Structure

├── Dataset/ # Zipped files and patient data Excel (stored in Google Drive)
├── unzipped_scans/ # Unzipped CT scans for each patient (stored in Google Drive)
├── Detection.py # Python code for feature extraction and analysis
├── .gitignore # Ignored files
├── README.md # Project description and instructions

## Data Availability

The dataset and unzipped scans are too large for GitHub. You can download them from the following links:

- [Dataset (zipped files and Excel)]([https://drive.google.com/your-dataset-link](https://drive.google.com/drive/folders/1IQbs6WpxOvAZoQMeeqOu-qdVSOjAp19i?usp=drive_link))
