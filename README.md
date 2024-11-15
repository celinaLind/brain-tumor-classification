# AI Brain Tumor Classification ~ 20 hours

User is able to upload an MRI scan image and have it classified as no tumor or one of the three main brain tumor typse (Glioma, Meningioma, or Pituitary). This classification is done by a model pretrained by Xtension or a Custom CNN (Convolutional Neural Network). The user is then able to gain a better understanding of the models "thought-process" by reviewing the saliency map or by reading the gemini-generated explanation based on the users understanding level.

*Note: The notebooks provided show the code, outputs, and notes.*
- "Project_2_AI..." notebook houses Transfer Learning - Xtension model and the Streamlit App
- "..." notebook houses the functional Custom CNN model and outputs

<iframe width="560" height="315" src="https://www.youtube.com/embed/Z6Iqy5IBMDg?si=takr1H079ldVdAKh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Table of Contents
- [Skills Used](#skills-used)
- [Development Issues](#development-issues)
- [Notes](#notes)

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
