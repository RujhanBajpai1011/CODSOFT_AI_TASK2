# 👁️ Face Detection

This project implements a simple **face detection** system using OpenCV's Haar Cascade classifiers. It identifies faces within an image and draws rectangles around them.

## **✨ Features**

* **Face Detection**: Utilizes the pre-trained Haar Cascade classifier to detect frontal faces.
* **Bounding Box Visualization**: Draws blue rectangles around the detected faces in the image.
* **Image Display**: Shows the processed image with detected faces.
* **Error Handling**: Basic handling for cases where the image cannot be read.

## **🛠️ Technologies Used**

* **Python**
* **OpenCV** (`cv2`): For image processing and face detection.
* `google.colab.patches.cv2_imshow`: For displaying images in Google Colab environments.

## **📦 Requirements**

You will need the following Python library:

* `opencv-python`

## **🚀 Getting Started**

### **Installation**

1. **Clone the repository (if applicable):**

```
git clone <repository_url>
cd <repository_name>
```

2. **Install the required Python package:**

```
pip install opencv-python
```

### **Usage**

1. **Image**: Make sure you have an image file (e.g., `Face_Sample.jpg` as referenced in the notebook) in the same directory as the Jupyter notebook (`Face_detection.ipynb`).

2. **Run**: Open `Face_detection.ipynb` in a Jupyter environment (like Google Colab) and run all the cells.

The notebook will then process the image, detect faces, and display the image with bounding boxes.

## **🧑‍💻 Contributing**

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please feel free to:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature-name).
3. Make your changes.
4. Commit your changes (git commit -m 'Add new feature').
5. Push to the branch (git push origin feature/your-feature-name).
6. Open a Pull Request.

## **📄 License**

This project is open-source and available under the MIT License.
