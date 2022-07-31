# Data Scientist Nanodegree: Capstone Project
# Dog_App

# Introduction:
This project aims at using a convolutional neural network (CNN) to predict dog breeds.

The process is to first determine if an image is a dog or a human:

If it's dog, determine which breed.

If it's a human, which dog breed it resembles the most

Thechnical details are available in this blog post: 

# Instructions:
1. Start by installing the libraries required : run pip install -r requirements.txt
2. Download the dog dataset at "https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip", unzip the folder and place the three files (test, train and valid) in the folder data/dog_images, create the folders if needed.
3. Download the human dataset at "https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip", unzip the folder and place the three files (test, train and valid) in the folder data/lfw, create the folders if needed.
4. Launch the notebook dog_app.ipynb and run every cell in order.



# File Tree
dog_app.ipynb
extract_bottleneck_features.py
README.md
requirements.txt


./bottleneck_features


./data
    ./lfw
    ./dog_images

./Test_Pictures
    Ana_de_Armas.jpg
    Border-Collie.jpg
    mix-golden-retrievers.jpg
    Schnauzer.jpg
    Papillon_dog.jpg
    Batman.jpg

./haarcascades
    haarcascade_frontalface_alt.xml

./images
    American_water_spaniel_00648.jpg
    Brittany_02625.jpg
    Curly-coated_retriever_03896.jpg
    Labrador_retriever_06449.jpg
    Labrador_retriever_06455.jpg
    Labrador_retriever_06457.jpg
    sample_cnn.png
    sample_dog_output.png
    sample_human_2.png
    sample_human_output.png
    Welsh_springer_spaniel_08203.jpg

./saved_models
    weights.best.from_scratch.hdf5
    weights.best.InceptionV3.hdf5
    weights.best.VGG16.hdf5
