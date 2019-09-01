# Web App for Image Classification Using Mobilenet

## Local Installation

### 1. Zip/Clone this Repo
$ git clone https://github.com/kenNicholaus/webapp-classify-mobilenet.git


### 2. Install Requiremnents
```shell
$ pip install -r requirements.txt
```
Make sure you have the following installed:
- tensorflow
- keras
- flask
- pillow
- h5py
- gevent


### 3. Run classify.py
Python 2.7 or 3.5+ are supported and tested.
```shell
$ python classify.py
```


### 4. Check http://127.0.0.1:5000/ or http://localhost:5000


### 5. Load Image..
-browse and load image


### 6. Click predict


### 7. Result will display the top prediction for the classified image with its probability



------------------

## Docker Installation

### Build and run an image for webapp-classify-mobilenet model 
```shell
$ cd webapp-classify-mobilenet
$ docker build -t webapp-classify-mobilenet .
$ docker run -d -p 5000:5000 webapp-classify-mobilenet 

------------------



Check Siraj's ["How to Deploy a Keras Model to Production"](https://youtu.be/f6Bf3gl4hWY) video. The corresponding [repo](https://github.com/llSourcell/how_to_deploy_a_keras_model_to_production).

[Building a simple Keras + deep learning REST API](https://blog.keras.io/building-a-simple-keras-deep-learning-rest-api.html)
