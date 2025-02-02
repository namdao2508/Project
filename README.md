## Inspiration
The inspiration behind this project comes from the importance of early detection of breast cancer.  By automating the classification of histopathology slides, we aim to assist pathologists and healthcare professionals in making faster and more accurate diagnoses.
## What it does
The project uses Convolutional Neural Networks to classify tumor images from histopathology slides as either benign or malignant. The model is trained and evaluated using key metrics like accuracy, precision, recall, and F1-score to ensure its reliability. By automating image classification, the model helps doctors detect cancerous cells more efficiently.
## How we built it
We built the model using Python with the TensorFlow/Keras framework for deep learning. Histopathology images were processed using OpenCV to resize and normalize the images. The model architecture consists of multiple CNN layers for feature extraction, followed by fully connected layers for classification. We evaluated the model's performance using scikit-learn metrics, ensuring high reliability.
## Challenges we ran into
Working with medical images required a lot of preprocessing, including resizing, normalization, and augmentation to improve model performance.
