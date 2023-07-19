# Font-Recognition-by-CNN
The aim of the project is to recognize fonts of SynthText in images.

The file SynthText.h5 has approximately 30,000 images, and each image has several sentences.

There are 7 kinds of fonts.

We use a machine learning (ML) model with the architecture of CNN, using the TensorFlow and Keras libraries, to create a predictive model.

Before creating the model, we preprocess the data and augment it to improve our model's accuracy.

At the end, we test our model on new data and achieve an impressive accuracy rate of 91.88%.

### Operating Instructions
First, download SynthText.h5 file from the link below. <br>
Then,run "preprocessing.ipynb" file in order to crop the letters form the images. After this step, all the cropped images will 
saved in adaptedImage.h5.<br> You either can download this file directly from the link below. <br><br>
Second, run "evaluation.ipynb" file for training the model on training datset and evaluate him on the test datasets. 


### Links to h5 files
For download  SynthText.h5 file, click  [here ](https://drive.google.com/file/d/1QAZCBHScr547_l64GeTBMOP0dIWUwc_1/view?usp=drive_link) <br />
You also can directly download adaptedImage.h5 from [here ](https://drive.google.com/file/d/12VuA-Yv4YcjiszoI3G6eGp9PD3d4QVev/view?usp=drive_link)
