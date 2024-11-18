# Cotton Wool Spot Detection Using Machine Learning

## Overview
This project utilizes a machine learning model to detect cotton wool spots in retinal images. By employing advanced image processing techniques and training a robust model, the project aims to aid in the early diagnosis of vision-related disorders. The model achieves a 75% accuracy rate with almost a 90% confidence level, offering a foundation for quicker decision-making in medical contexts.

## Features
- **Image Annotation**: Annotated over 200 retinal images to prepare a comprehensive training and validation dataset.
- **Model Training**: Trained a machine learning model using scikit-learn and TensorFlow for high accuracy in detecting cotton wool spots.
- **Performance Optimization**: Improved detection accuracy by 15% through testing and optimization on unannotated datasets.
- **Medical Insights**: Provided insights for early diagnosis, enabling faster and more informed medical decisions.

---

## Dataset
### Dataset model
- The dataset is contained in this folder that includes over 200 retinal images annotated with cotton wool spots.
- Images are preprocessed using OpenCV for noise reduction and feature enhancement.
- Training data is in the train folder and the validation dataset is in the val folder
- The label folder has the normalized coordinates for a labeled object in both the training and validation images
- The predict has some of the images that are being used for testing the model

### Annotated files
- This folder has the files for all the Annotated images
-  The COCO folder refers to files formatted in the COCO (Common Objects in Context) dataset format
-  This folder contains a subset of the main dataset that has been filtered based on certain criteria (e.g., removing noisy annotations, irrelevant classes, or poor-quality images).
-  The VGG folder refers to files formatted in theVGG (Visual Geometry Group) dataset format

### runs/segment
- This folder contains the predicted imaged with the accuracy in decimal form on the train, validation and predict datasets.

---

### Performance Metrics
- **Accuracy**: 75%
- **Confidence Level**: 75%-80%
- **Post-Optimization Improvement**: 15%


## Learn More
- To learn about TensorFlow: [TensorFlow Documentation](https://www.tensorflow.org/)
- To understand scikit-learn: [scikit-learn Documentation](https://scikit-learn.org/)
- Explore image processing with OpenCV: [OpenCV Documentation](https://opencv.org/)
