# Plant-Disease-Prediction-model based on Convolutional Neural Network.
## Table of Contents.
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run](#run)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [License](#license)
  * [Credits](#credits)
  
  ## Demo
  Link. (Deployment Link is on progress...).
  
  ## Overview
This is a simple image classification Flask app trained on the top of Keras API. The trained model (`Plant-Disease-Prediction/Model/Various Plant Disease Detection Model1.h5`) takes an image (from Plant Disease) as an input and predict the class of image from __diseased cotton leaf, diseased cotton plant, fresh cotton leaf, fresh cotton plant, Pepper bell Bacterial spot, Pepper bell healthy, Potato Early blight, Potato healthy, Potato Late blight, Tomato Target Spot, Tomato Tomato mosaic virus, Tomato Tomato YellowLeaf Curl Virus, Tomato Bacterial spot, Tomato Early blight, Tomato healthy, Tomato Late blight, Tomato Leaf Mold, Tomato Septoria leaf spot, Tomato Spider mites Two spotted spider mite__ denomination.

## Motivation
What could be a perfect way to utilize unfortunate lockdown period? Like most of you, I spend my time in cooking, Netflix, coding and reading some latest research papers on weekends. This idea came into my mind when I goto my village and see that how the farmers were seeing at the plants for different diseases. They were paying high fees to the plant disease specialists. So I utilize my best knowledge to overcome their expenses. 

## Technical Aspect
This project is divided into two part:
1. Training a deep learning model using Keras and by [.ipynb file](https://github.com/IamVicky90/Plant-Disease-Prediction/blob/main/.ipynb%20notebooks/Plant%20Disease%20Detection.ipynb).
2. Building and hosting a Flask web app on Heroku(it's not done yet).

## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [downloading it](https://github.com/IamVicky90/Plant-Disease-Prediction/archive/main.zip):
```bash
pip install -r requirements.txt
```
## Run
To run the app in a local machine, shoot this command in the project directory:
__Run the follwing command after installing requirements.txt__
```bash
python app.py
```
## Directory Tree 
```
├── .ipynb notebooks
│   ├── .ipynb_checkpoints
│   ├── Plant Disease Detection.ipynb
│   ├── Predictions on Test data and classification Report.ipynb
│   └── debug.log
├── Images
│   ├── 1.PNG
│   ├── 2.PNG
│   ├── capture.PNG
├── Model
│   ├── Various Plant Disease Detection Model1.h5
├── Static
│   ├── Cotton Disease Images
│   ├── Images
│   ├── User Upload

├── Various Plant Disesse Detection Prediction DataSet
│   ├── Test
    │   ├── diseased cotton leaf
    │   ├── diseased cotton plant
    │   ├── fresh cotton leaf
    │   ├── fresh cotton plant
    │   ├── Pepper bell Bacterial spot
    │   ├── Pepper bell healthy
    │   ├── Potato Early blight
    │   ├── Potato healthy
    │   ├── Potato Late blight 
    │   ├── Tomato Target Spot 
    │   ├── Tomato Tomato mosaic virus
    │   ├── Tomato Tomato YellowLeaf Curl Virus
    │   ├── Tomato Bacterial spot
    │   ├── Tomato Early blight
    │   ├── Tomato healthy
    │   ├── Tomato Late blight
    │   ├── Tomato Leaf Mold
    │   ├── Tomato Septoria leaf spot
    │   ├── Tomato Spider mites Two spotted spider mite
│   ├── Train
    │   ├── diseased cotton leaf
    │   ├── diseased cotton plant
    │   ├── fresh cotton leaf
    │   ├── fresh cotton plant
    │   ├── Pepper bell Bacterial spot
    │   ├── Pepper bell healthy
    │   ├── Potato Early blight
    │   ├── Potato healthy
    │   ├── Potato Late blight 
    │   ├── Tomato Target Spot 
    │   ├── Tomato Tomato mosaic virus
    │   ├── Tomato Tomato YellowLeaf Curl Virus
    │   ├── Tomato Bacterial spot
    │   ├── Tomato Early blight
    │   ├── Tomato healthy
    │   ├── Tomato Late blight
    │   ├── Tomato Leaf Mold
    │   ├── Tomato Septoria leaf spot
    │   ├── Tomato Spider mites Two spotted spider mite
│   ├── Val
    │   ├── diseased cotton leaf
    │   ├── diseased cotton plant
    │   ├── fresh cotton leaf
    │   ├── fresh cotton plant
    │   ├── Pepper bell Bacterial spot
    │   ├── Pepper bell healthy
    │   ├── Potato Early blight
    │   ├── Potato healthy
    │   ├── Potato Late blight 
    │   ├── Tomato Target Spot 
    │   ├── Tomato Tomato mosaic virus
    │   ├── Tomato Tomato YellowLeaf Curl Virus
    │   ├── Tomato Bacterial spot
    │   ├── Tomato Early blight
    │   ├── Tomato healthy
    │   ├── Tomato Late blight
    │   ├── Tomato Leaf Mold
    │   ├── Tomato Septoria leaf spot
    │   ├── Tomato Spider mites Two spotted spider mite

├── templates
│   ├── diseased cotton leaf.html
│   ├── diseased cotton plant.html
│   ├── fresh cotton leaf.html
│   ├── fresh cotton plant.html
│   ├── Pepper bell Bacterial spot.html
│   ├── Pepper bell healthy.html
│   ├── Potato Early blight.html
│   ├── Potato healthy.html
│   ├── Potato Late blight.html
│   ├── Tomato Target Spot.html
│   ├── Tomato Tomato mosaic virus.html
│   ├── Tomato Tomato YellowLeaf Curl Virus.html
│   ├── Tomato Bacterial spot.html
│   ├── Tomato Early blight.html
│   ├── Tomato healthy.html
│   ├── Tomato Late blight.html
│   ├── Tomato Leaf Mold.html
│   ├── Tomato Septoria leaf spot.html
│   ├── Tomato Spider mites Two spotted spider mite.html
├── Procfile
├── README.md
├── app.py
├── requirements.txt
```


