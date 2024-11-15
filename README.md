# AI Brain Tumor Classification ~ 20 hours

User is able to upload an MRI scan image and have it classified as no tumor or one of the three main brain tumor typse (Glioma, Meningioma, or Pituitary). This classification is done by a model pretrained by Xtension or a Custom CNN (Convolutional Neural Network). The user is then able to gain a better understanding of the models "thought-process" by reviewing the saliency map or by reading the gemini-generated explanation based on the users understanding level.

*Note: The notebooks provided show the code, outputs, and notes.*
- "Project_2_AI..." notebook houses Transfer Learning - Xtension model and the Streamlit App
- "..." notebook houses the functional Custom CNN model and outputs

### Video Walkthrough
[![Brain Tumor Classification Walkthrough](https://img.youtube.com/vi/Z6Iqy5IBMDg/0.jpg)](https://www.youtube.com/watch?v=Z6Iqy5IBMDg)

## Table of Contents
- [Skills Used](#skills-used)
- [Development Issues](#development-issues)
- [Notes](#notes)
- [Resources](#resources)

## Skills Used
- Python
- Tensorflow
- Gemini 1.5-Flash
- Neural Networks
- Computer Vision
- Sklearn
- Seaborn
- Pandas
- Streamlit
- Transfer Learning
- Xtension
- Convolutional Neural Network
- Google Colab
- Kaggle

## Development Issues

#### Excessive Model Training Time
This project took longer than anticipated due to Google Colab first taking an excessive amount of time to train the custom CNN model. The last time was over 50 minutes and it didn't get passed the first epoch.

#### Two different Notebooks
Due to the excessive training time, colab reached its GPU limit and I had to switch to using Kaggle for the remainder of my CNN model training.

## Notes

##### Saliency Maps
These are images that visually map the focus of the model. For this project the cyan shading over the image is where the model was "looking" to classify the tumor.

#### Transfer Learning
This utilizes a larger pretrained model (Xtension) to train a smaller more specialized model.

#### [Streamlit](https://streamlit.io/)
An open-source Python framework for building and sharing applications.

## Resources
- [Kaggle Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- [What is a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk)
- [How a Neural Network Learns](https://www.youtube.com/watch?v=IHZwWFHWa-w)
- [What is Convolution](https://www.youtube.com/watch?v=KuXjwB4LzSA)
- [Interactive CNN Explainer](https://poloclub.github.io/cnn-explainer/)
- [What is Transfer Learning?](https://builtin.com/data-science/transfer-learning)
- [Saliency Map Implementation](https://medium.com/@bijil.subhash/explainable-ai-saliency-maps-89098e230100)
