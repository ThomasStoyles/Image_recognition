# Image Recognition AI

This project is an image recognition AI model trained on the CIFAR-10 dataset, capable of classifying images into ten categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.
It features a user-friendly graphical interface built with Python, allowing users to upload images and receive real-time classification results.

## Features

- **High Accuracy**: Achieves up to 96% accuracy on the CIFAR-10 dataset.
- **Graphical User Interface**: Interactive GUI for easy image upload and classification.
- **Pre-trained Model**: Includes a pre-trained model (`model1_cifar_10epoch.h5`) for immediate use.
- **Customizable**: Codebase is structured for easy retraining and enhancement.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ThomasStoyles/Image_recognition.git
   cd Image_recognition
   ```

2. **Install Dependencies**:
   Ensure you have Python 3 installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Launch the GUI**:
   ```bash
   python gui.py
   ```

2. **Classify an Image**:
   - Use the GUI to upload an image.
   - The model will process the image and display the predicted category.

## Model Details

- **Architecture**: Convolutional Neural Network (CNN) tailored for image classification.
- **Dataset**: Trained on the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes.
- **Training**: The model was trained for 10 epochs, balancing performance and training time.

## Future Improvements

- **Enhanced Accuracy**: Further training and hyperparameter tuning could improve model performance.
- **Expanded Categories**: Incorporate additional datasets to recognize more object categories.
- **Advanced GUI Features**: Implement drag-and-drop functionality and batch image processing.

## License

This project is open-source and available under the [MIT License](LICENSE).
