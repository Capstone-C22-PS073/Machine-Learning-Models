# Machine Learning Documentation

Local ENV Requirement:
 - Tensorflow 2.9.0 (GPU)
 - NVIDIA GPU
    - NVIDIA GPU Driver version 450.80.02 or higher.
    - CUDA Version 11.*
    - cuDNN SDK 8.1.*
 - Python 3.8.13
 - Matplotlib
 - imghdr

# How to run in local
 1. Make sure the requirements above have been installed
 2. Clone Repository to your local
 3. Open Capstone ML - Toursight.ipynb
 4. Run the code (for detail information see comments in the code)
 5. Output Model saved in saved_model folder (There are 2 type of outptu model, a .pb and .tflite)

# Directory
    .
    ├── Datasets                        # Contains Datasets used in machine learning.
    ├── Saved Model                     # Contains Versions of Saved Model (.pb and .tflite)
    ├── urls                            # Datasets urls source
    ├── testing                         # Folder to test machine learning prediction, contain an image to predict
    ├── Capstone ML - Toursight.ipynb   # Source code of the program
    └── README.md
