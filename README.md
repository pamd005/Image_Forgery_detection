
# 🕵️‍♂️ Image Forgery Detection using ELA and CNN

This project focuses on detecting forged or tampered images using a deep learning model trained on Error Level Analysis (ELA) processed images. It uses convolutional neural networks (CNNs) and essential preprocessing techniques to identify discrepancies introduced by digital forgeries.

## 🧠 Overview

Image forgery is a common technique used to manipulate visual content. Detecting such tampering is crucial in digital forensics, journalism, and verification processes. This project uses ELA (Error Level Analysis) to highlight areas in images that may have been digitally altered and feeds the results into a CNN to learn patterns of manipulation.

## 📁 Project Structure

* `image_forgery_detection.ipynb`: Main Jupyter Notebook containing:

  * Image preprocessing using ELA
  * CNN model creation and training
  * Performance visualization
  * Utility functions for image loading and classification

## 🛠️ Key Technologies

* **Python**
* **TensorFlow / Keras**
* **OpenCV**
* **PIL (Python Imaging Library)**
* **Matplotlib, NumPy, scikit-image**

## 🧪 How It Works

1. **ELA Conversion**: Converts images to ELA format to amplify areas with different compression levels.
2. **CNN Model**: Trained on ELA images to classify between original and tampered images.
3. **Metrics**: Accuracy and loss are used to evaluate the model’s performance.

## 🚀 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/pamd005/image-forgery-detection.git
cd image-forgery-detection

# Install dependencies
pip install -r requirements.txt
```

If not using a `requirements.txt`, install packages manually:

```bash
pip install tensorflow keras pillow scikit-image opencv-python matplotlib numpy
```

## 🖼️ Example Images

* Real and tampered images are processed using ELA and displayed to highlight forgery.
* The CNN is trained on processed datasets to distinguish between forged and authentic images.

## 📊 Results

* The model achieves promising accuracy for distinguishing forged vs. authentic images.
* ELA preprocessing significantly enhances detection performance.

## ✅ TODO

* Add more tampered datasets for robustness
* Improve model generalization using transfer learning
* Create a GUI or mobile app interface

## 🤝 Contributing

Contributions are welcome! Fork this repository and open a pull request.

## 📝 License

This project is licensed under the MIT License.
