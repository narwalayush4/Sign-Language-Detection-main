# Project-Sign-Language-Detection

# Tech Stack :
1. Tensorflow
2. Keras
3. OpenCV
4. Numpy
5. Matplotlib

# Running Instructions :

1. Clone the Repository.
2. Go to predictor.ipynb
3. Run all the shells
4. Running the last shell will open up a camera screen where you can place your hand in the Region of Interest, and make signs for numbers from 0 to 9. The prediction will appear on the screen.

 Demo Link : https://drive.google.com/file/d/1lm7-CvF8i4UVzs0HjTUiJrCrqVJWpegB/view?usp=sharing

# Results :

Achieved a final accuracy of 96.2%. Experimented with various CNN architectures and dropout rates. Also tried bagging and boosting for better performance.

# Creating your own Dataset :

Additionally, you can create your own dataset using create_datasets.ipynb. Run all the shells. The last shell will open up a camera screen, which will analyze and detect the background for 60 frames. You can then place your hand inside the Region of Interest, and make the sign you want to record. The camera will confire your hand for 300 frames, and then take 300 pictures and save them in a folder as specified in the path. This can be done for as many signs as you like. The number of pictures to be taken can also be adjusted according to your needs.

# Training Different Models :

You can train the models using train_CNN.ipynb. Run all the shells. If you generated your own dataset, make sure you specify the path to training and testing dataset correctly. The model can be saved as a .h5 file, and named according to your specifications. The current implementation has 6 models saved, which are used to make predictions in predicter.ipynb via bagging. 
