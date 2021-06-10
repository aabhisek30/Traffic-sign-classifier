# Traffic-sign-classifier

## Project Dependency 

1. Pandas 
2. Numpy
3. Matplotlib 
4. Tensorflow
5. keras
6. Flask
7. OS
8. Pillow


## Dataset 

German Traffic Dataset - https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

## Information about class of the dataset

There are 43 classes in the Dataset

![image](https://user-images.githubusercontent.com/67454437/121567147-ddeb5200-ca3b-11eb-9f71-b0ff13ba0c7f.png)

## Model 

I have used Convoluational Neural Network for learning the features. 

![image](https://user-images.githubusercontent.com/67454437/121568968-e9d81380-ca3d-11eb-955d-cf10020e7968.png)

## Model variation

I have trained 3 different CNN model 

1. Model trained on image size 30 X 30
2. Model trained on image size 50 X 50
3. Model trained on Data augmented on image size 30 X 30 


## Result

| Model                 | Accuracy | 
|:--------------------- |:--------:| 
| CNN 30 X 30           | 93.58    | 
| CNN 50 X 50           | 95.16    |   
| CNN Data Augmentation | 94.53    |    


## Running program 

Run traffic_sign_classifier.py 

*_Format of the uploaded images should be .jpg or .png

It will use weight of 2nd model to classify uploaded the image

The Uploaded images are saved in image folder

![image](https://user-images.githubusercontent.com/67454437/121570100-28ba9900-ca3f-11eb-8665-9bd57fcf677a.png)
