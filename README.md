# Traffic Signs Classification using CNN
The objective of the project is to detect traffic signs using image dataset. Convolutional Neural Network is used to classify the images. The output class consists of 43 different traffic signs.

# Dataset Information

The training archive contains 43 different type of traffic signs.<br />
Some images of the dataset:<br />
<img align='center' src="https://github.com/gnurt2041/Traffic_Signs_Classification/blob/main/image/dataset.jpg" width="700">

**Paperwithcode dataset link:** https://paperswithcode.com/dataset/gtsrb

**Environment:** Google Colab

**The directory structure:**
```
Traffic_Signs_Classification/
	├── signsdata/
        ├── train.p
        ├── test.p
        └──  valid.p
  └──main/
        └── traffic_signs_classification.ipynb
```
# Libraries

<li>pickle
<li>os
<li>wget
<li>numpy
<li>seaborn
<li>tensorflow
<li>scikit-learn
<li>livelossplot

# Neural Network

<li>CNN Architecture

<h2><img align='center' src="https://github.com/gnurt2041/Traffic_Signs_Classification/blob/main/image/plot_cnn.png" width="700"><h2>

# Result
<h3><img align='center' src="https://github.com/gnurt2041/Traffic_Signs_Classification/blob/main/image/result.png" width="700"><h3>

**Accuracy:** ~96.65%( with class_weight ), look the above code to more detail
