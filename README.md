# 🐶 Dog vs Cat Image Classification using Python and OpenCV

## 📌 Project Overview

The **Dog vs Cat Image Classification** project focuses on developing an image classification system that distinguishes between two categories of animal images: Dogs and Cats.

Image classification is an important application of Computer Vision and Machine Learning, where computers are trained to identify and categorize objects based on visual information.

In this project, Python and OpenCV are used to perform image preprocessing operations, including reading images, converting them into grayscale, resizing them into a standardized dimension, and transforming them into numerical feature arrays.

The processed image data is prepared for further Machine Learning model development and classification.

## 🎯 Project Objectives

The main objectives of this project are:

- To understand the fundamentals of image classification using Computer Vision.
- To work with a dataset containing images of Dogs and Cats.
- To perform image preprocessing using OpenCV.
- To convert images into grayscale format.
- To resize images into a uniform dimension of 28 × 28 pixels.
- To transform image data into numerical arrays using NumPy.
- To prepare image features and corresponding labels for classification.
- To understand the complete workflow of an image classification project.

## 🛠️ Technologies and Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| OpenCV (cv2) | Image processing and manipulation |
| NumPy | Numerical operations and array manipulation |
| Jupyter Notebook | Development and experimentation |
| OS Module | File and directory handling |
| Matplotlib | Image visualization, if used |

## 📂 Dataset Description

The project uses a Cats vs Dogs image dataset containing two image categories:

- **Cat:** Images belonging to the Cat category.
- **Dog:** Images belonging to the Dog category.

The dataset contains thousands of images with different backgrounds, orientations, sizes, and visual characteristics.

The images are processed to ensure consistency before being used for classification.

**Note:** The original dataset is not included in this repository because of its large file size. Users must download the dataset separately and configure the appropriate dataset path.

## ⚙️ Project Workflow

### 1. Importing Required Libraries

The project uses Python libraries such as OpenCV and NumPy to perform image processing and numerical operations.

### 2. Loading the Dataset

The dataset is organized into separate folders representing Cats and Dogs. Python's OS module is used to access directories and retrieve image files.

### 3. Image Reading

OpenCV's `imread()` function is used to read the images from the dataset.

### 4. Grayscale Conversion

Images are converted into grayscale format to simplify image processing and reduce the complexity of the input data.

### 5. Image Resizing

All images are resized to a standard dimension of **28 × 28 pixels** using OpenCV's `resize()` function.

This ensures that every image has a consistent shape.

### 6. Feature Extraction

The resized images are converted into one-dimensional numerical arrays using NumPy's `flatten()` function.

These flattened arrays represent the pixel intensity values of each image.

### 7. Label Assignment

Each image is assigned a corresponding label based on its parent folder.

This creates two components:

- **Features (X):** Flattened image pixel values.
- **Labels (y):** Corresponding image categories (Cat or Dog).

### 8. Data Preparation

The processed image features and labels are organized into suitable structures for subsequent Machine Learning classification.

## 🔄 Image Processing Pipeline

Image Dataset → Image Reading → Grayscale Conversion → Image Resizing (28 × 28) → Flattening → Feature Preparation → Label Assignment → Classification

## 📁 Project Structure

```text
Dog-Vs-Cat-Image-Classification/
│
├── Cats vs Dogs Recognition using OpenCV.ipynb
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
```

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/SaiLeela88/Dog-Vs-Cat-Image-Classification.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Dog-Vs-Cat-Image-Classification
```

### Step 3: Install Required Libraries

```bash
pip install opencv-python numpy matplotlib jupyter
```

### Step 4: Download the Dataset

Download the Cats vs Dogs dataset and organize the images into separate Cat and Dog folders.

### Step 5: Configure the Dataset Path

Update the dataset directory path in the Jupyter Notebook according to your local system.

### Step 6: Run the Notebook

```bash
jupyter notebook
```

Open `Cats vs Dogs Recognition using OpenCV.ipynb` and execute the cells sequentially.

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

- Understanding Computer Vision fundamentals.
- Reading and processing image datasets using OpenCV.
- Performing grayscale conversion and image resizing.
- Understanding pixel intensity values and image representations.
- Converting images into numerical feature vectors.
- Working with NumPy arrays.
- Handling image datasets using Python.
- Understanding the initial stages of an image classification pipeline.

## 🔮 Future Enhancements

The project can be further enhanced by:

- Implementing Machine Learning classification algorithms.
- Exploring Convolutional Neural Networks (CNNs).
- Improving classification performance through image augmentation.
- Experimenting with different image dimensions and preprocessing techniques.
- Evaluating models using accuracy, precision, recall, and F1-score.
- Developing an interactive web application for image prediction.

## 👩‍💻 Author

**Sai Leela**

- GitHub: [SaiLeela88](https://github.com/SaiLeela88)
- LinkedIn: [Sai Leela](https://www.linkedin.com/in/sai-leela-958497371/)

---

⭐ If you find this project useful, consider giving the repository a star!

**Thank you for visiting my project!**
