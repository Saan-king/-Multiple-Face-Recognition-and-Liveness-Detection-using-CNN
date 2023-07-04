# Multiple Face Recognition and Liveness Detection using CNN

![Python](https://img.shields.io/badge/python-v3.8-blue)
![TensorFlow](https://img.shields.io/badge/tensorflow-v2.6.0-orange)
![OpenCV](https://img.shields.io/badge/opencv-v4.5.3-green)

This repository contains the code for a project that combines multiple face recognition and liveness detection using Convolutional Neural Networks (CNNs). The project aims to provide an accurate and robust solution for identifying and verifying human faces while ensuring the liveness of the detected faces.

## Features

- **Multiple Face Recognition:** The system is capable of recognizing and identifying multiple faces simultaneously in real-time using a CNN-based face recognition model.
- **Liveness Detection:** To prevent spoofing attacks and ensure the liveness of the detected faces, the project incorporates a liveness detection mechanism. It can distinguish between real human faces and non-living objects or printed images.
- **Deep Learning Framework:** The implementation is built using TensorFlow, a popular deep learning framework, which allows for efficient training and inference of CNN models.
- **Real-time Processing:** The system operates in real-time, making it suitable for various applications such as access control, attendance systems, or surveillance systems.
- **Easy Integration:** The codebase is designed to be modular and easily integrable into other projects or applications.

## Installation

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Navigate to the project directory:
   ```
   cd your-repo-name
   ```

3. Create a virtual environment (optional but recommended):
   ```
   python3 -m venv env
   source env/bin/activate
   ```

4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Prepare the dataset:
   - Create a directory named `dataset` and organize your face images in subdirectories based on the person's name. Each subdirectory should contain images of only one person.
   - Ensure that each image contains only the face region of the respective person.

2. Train the face recognition model:
   - Run the following command to train the CNN face recognition model on your dataset:
     ```
     python train.py --dataset dataset --model models/model.h5
     ```

3. Run the application:
   - Execute the following command to start the face recognition and liveness detection application:
     ```
     python main.py --model models/model.h5
     ```

4. Interact with the application:
   - The application will open a video stream and display recognized faces with bounding boxes.
   - It will also indicate whether the detected face is live or not.
   - Press `q` to quit the application.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please create a new issue or submit a pull request. Make sure to follow the existing code style and provide relevant documentation.


## Acknowledgements

- The face recognition model used in this project is based on the work of Analysis on Face Recognition based on five different viewpoint of face images using MTCNN
and FaceNet By Al-imran 15201007 Baniamin
Shams 15301030 Faysal Islam Nasim 15201051.
2019..
- The liveness detection mechanism is inspired by .

## Contact

For any questions or inquiries, please contact msathyaanand@gmail.com.

Happy coding!
