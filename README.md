# Metal Surface Defect Classification using Convolutional Neural Network

The objective of this project is to build a Convolutional Neural Network (CNN) algorithm to classify metal surface defects. The dataset for this project was obtained from the NEU Metal Surface Defects Database. The dataset comprises grayscale images of six distinct types of surface defects commonly found in hot-rolled steel strips. The defect classes include rolled-in scale (RS), patches (Pa), crazing (Cr), pitted surface (PS), inclusion (In), and scratches (Sc). Each defect type is represented by 300 samples, resulting in a total of 1,800 images in the dataset.

## Datasets
The dataset used in this project is the NEU Metal Surface Defects Database, which contains grayscale images of different surface defects commonly found in metal surfaces. The dataset is distributed across six classes, and each class represents a specific type of surface defect. 

## Model Architecture
The project utilizes a Convolutional Neural Network (CNN) for the classification of metal surface defects. The CNN architecture includes multiple convolutional and pooling layers, followed by fully connected layers with dropout regularization. The model is trained on the provided training dataset and validated on a separate validation dataset.

## Model Evaluation
The trained model is evaluated on a test dataset to assess its performance. The evaluation includes metrics such as accuracy, precision, recall, F1-score, and a confusion matrix. These metrics provide insights into the model's ability to classify different surface defect types accurately.

## Output Comparison
A side-by-side comparison of the predicted and actual defect images is available in the file [outputImg.png](outputImg.png). This comparison visually demonstrates the model's performance by showcasing its predictions alongside the ground truth labels.
