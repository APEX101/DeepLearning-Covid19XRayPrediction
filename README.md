
# CovidXRayPrediction-CNN

<p float="left">
<img src=normal.jpeg width="30%"  height="250">
 <img src=effected.jpeg width="30%" height="250" >
</p>



## 📝 Overview
 
 Given Image Data of Chest X Ray.Predicts whether the patient is effected by Covid19 or Normal using Covolutional Neural Networks.
 Trained on Google Colab by Transfer Learning using ResNet50V2 Model.
    
## 🧰 Technical Aspects

- Traning on GoogleColab.
- Image Data preprocessing.
- Data Visualization and Exploratory Data Analysis.
- Image Data Normalization and Scaling.
- Using Image Data generator for Image Data Augmentation and ImageDataGenerator flow from directory for Class Batch Division to  train on.
- Training by Transfer Learning using ResNet50V2 Model.
- Compiled using AdamOptmizer as optmizer and binary_crossentropy as the loss function as its binary class classification problem.
- Solving Overfitting issues using EarlyStoppings Callbacks and Dropout Layers in Network.
- Hyperparameter Tuning the Algorithms yielding best results.
- Testing the model on custom reallife XRay Image data.
## ⏳ DataSet

https://www.kaggle.com/alifrahman/chestxraydataset
## 🖥️ Installation
### 🛠️ Requirement

* TensorFlow 2
* Keras
* Scikit-Learn
* Seaborn
* Matplotlib
* Pandas
* Numpy


    
## ⚙️ Tech Stack
<p float="left">
<img src="https://john.soban.ski/images/Fast_And_Easy_Regression_With_Tensorflow_Part_2/00_Tf_Keras_Logo.png" width="30%" >
<img src="https://i2.wp.com/softwareengineeringdaily.com/wp-content/uploads/2016/09/scikit-learn-logo.png?resize=566%2C202&ssl=1" width="40%" >
</p>
<img src="https://fiverr-res.cloudinary.com/images/q_auto,f_auto/gigs/187550926/original/cde47296f9d02346b6561eee753741d7272bfce6/do-data-analysis-in-python-using-numpy-pandas-matplotlib-seaborn.jpg" width="70%" >
