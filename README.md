<h1 align="center">
  <img align="center" src="https://github.com/Recycraft/.github/blob/main/assets/racycraft.jpg"  width="200"></img>
<br>
Recycraft
</h1>

#  Bangkit 2022 Product Based Capstone

### Team ID : C22-PS285

### Members : 
* (M2007F0776) - [Wahyu Adi Nugroho](https://github.com/wahyu-adi-n) - Universitas Dian Nuswantoro
* (M2007F0777) - [Raphael Adhimas Aryandanu Santoso](https://github.com/raphaeldanu) - Universitas Dian Nuswantoro
* (A2007F0724) - [Alfonda Steven Wahyudi](https://github.com/alfondasteven) - Universitas Dian Nuswantoro
* (A2009F0915) - [Firstiannisa Rizki](https://github.com/ftiannisa) - Universitas Gunadarma
* (C2009F0934) - [Zekri Fitra Ramadhan](https://github.com/yusrankun) - Universitas Gunadarma
* (C7009F0926) - [Muhammad Rafi Ramadhan](https://github.com/rafi016) - Universitas Gunadarma

# Recyraft-Machine Learning
This project is our final project for Google Bangkit Academy 2022.

**Recyraft-Android :**
[RecyraftApp]()

**Recyraft-Cloud :**
[RecyraftCloud]()

**Machine Learning :** 
Building two models that include : [scraps type classification](https://github.com/Recycraft/machine-learning/tree/main/scraps-type-classification) and [scraps classification detection](https://github.com/Recycraft/machine-learning/tree/main/scraps-classification-detection). Build process using *baseline experiment, dropout, flatten*. In this project, we use simple Convolutional Neural Network and pre-trained model or transfer learning by *Inceptionv3 and Xception*. The model was saved with *model.tflite* and chosen by the [best model]() for deployment.

## Machine Learning Task :
1. Scraps Type Classification (Binary Classification)
2. Scraps Classification & Detection (Multiple Classification)

## Datasets (Kaggle and Github) :
1. Recycleable or Organic :
  * [Waste Classification Data](https://www.kaggle.com/datasets/techsash/waste-classification-data)
2. Scraps with 8 class ( Bottle-Plastic, Can, Cardboard, Glass-Plastic, Paper, Plastic, Spoon-Plastic, and Styrofoam) :
  * [Garbage Classification - 12 Classes](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)
  * [Most Common Recyclable and Non-Recyclable Objects](https://www.kaggle.com/datasets/ashwinshrivastav/most-common-recyclable-and-nonrecyclable-objects)
  * [TrashBox](https://github.com/nikhilvenkatkumsetty/TrashBox)
  * Crapping Image on Google Search (Manually)

## Features :
1. EDA (Exploratory Data Analysis) for Image Classification
2. Preprocessing Data and Image
3. Image Augmentation
4. Simple CNN
5. InceptionV3
6. Xception
7. TFLite x labels 

## Prerequisites :
1. [Anaconda (Jupyter Notebook)](https://test-jupyter.readthedocs.io/en/latest/install.html) or [Google Colab](https://colab.research.google.com/)
2. [Python](https://www.python.org/downloads/) version 3.7 or above
3. Tensorflow 2.8 or latest version
4. Tensorflow Lite
5. Keras API
6. Kaggle API Token → [Generate](https://github.com/Kaggle/kaggle-api#api-credentials)

## Documentation :
1. Import Library and Preparing Dataset
2. Splitting and Checking Dataset
3. Preprocessing Dataset and Perform Data Augmentation
4. Make ML Model, Build and Training Dataset
5. Model Evaluation
6. Create Prediction Data
7. Get Result Prediction
8. Saved Model and Convert to TFLite Model

## References (Paper/Journal/Article) :
1. https://iopscience.iop.org/article/10.1088/1755-1315/775/1/012010/meta
2. https://www.mdpi.com/2313-4321/7/1/9
3. https://www.scirp.org/pdf/jcc_2021011322480971.pdf
4. https://ieeexplore.ieee.org/abstract/document/9395916
