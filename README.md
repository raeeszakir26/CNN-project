This project uses a Convolutional Neural Network (CNN) to recognize digits from the Street View House Numbers (SVHN) dataset. The dataset contains images of house numbers captured from Google Street View.
Installation
To run this project, you'll need Python and some libraries:
•	TensorFlow
•	NumPy
•	Matplotlib
•	scikit-learn
•	SciPy
You can install the required libraries using pip:
bash
Copy code
pip install tensorflow numpy matplotlib scikit-learn scipy
Usage
1.	Clone the Repository:
bash
Copy code
git clone https://github.com/raeeszakir26/svhn-digit-recognition.git
cd svhn-digit-recognition
2.	Download the SVHN Dataset:
Get the SVHN dataset from here and place the .mat files in the project folder.
3.	Run the Script:
Execute the training and evaluation script:
bash
Copy code
python svhn_digit_recognition.py
Model Overview
The CNN model includes:
•	Convolutional layers to extract features from images.
•	MaxPooling layers to reduce size and complexity.
•	A Flatten layer to prepare data for the dense layers.
•	Dense layers for classification of the digits.
Results
The model achieves about 93% accuracy on the test set. A confusion matrix is used to show how well it performs on different digits.

