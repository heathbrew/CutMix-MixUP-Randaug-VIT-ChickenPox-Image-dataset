# CutMix-MixUP-Randaug-VIT-ChickenPox-Image-dataset
CutMix-MixUP-Randaug-VIT-ChickenPox Image dataset
#Dataset
The Monkeypox Skin Image Dataset is available on Kaggle and can be downloaded from this https://www.kaggle.com/datasets/dipuiucse/monkeypoxskinimagedataset. The dataset contains 1849 images of monkeypox skin lesions, with labels indicating the type of lesion. The dataset is stored as a zip file, which needs to be extracted before loading the images.

#Preprocessing Techniques
Various preprocessing techniques are applied to the images before training the model. The techniques used are:

Cut Mix data augmentation for image classification
MixUp augmentation for image classification
Rand Augment for Image Classification for Improved Robustness

#Model Architecture
The model used in this project is the Vision Transformer (ViT), a transformer-based neural network architecture designed for image classification tasks.
https://keras.io/examples/vision/image_classification_with_vision_transformer/

#Training and Evaluation
The model is trained on the preprocessed dataset using the fine-tuning techniques. The performance of the model is evaluated on the validation and testing datasets. Metrics used to evaluate the model's performance include accuracy, precision, recall, F1-score and Confusion Matrix.
