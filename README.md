# Font-Recognition-by-CNN
The aim of the project is to recognize fonts of SynthText in images.

The file SynthText.h5 has approximately 30,000 images, and each image has several sentences.

There are 7 kinds of fonts.

We use a machine learning (ML) model with the architecture of CNN, using the TensorFlow and Keras libraries, to create a predictive model.

Before creating the model, we preprocess the data and augment it to improve our model's accuracy.

At the end, we test our model on new data and achieve an impressive accuracy rate of 91.88%.

### Operating Instructions
irst, download the SynthText.h5 file from the link below.

Then, run the "preprocessing.ipynb" file to crop the letters from the images. After this step, all the cropped images will be saved in "adaptedImage.h5."

You can download the "adaptedImage.h5" file directly from the link below.

Second, run the "evaluation.ipynb" file to train the model on the training dataset and evaluate it on the test dataset.


### Links to h5 files
To download the SynthText.h5 file, click  [here ](https://drive.google.com/file/d/1QAZCBHScr547_l64GeTBMOP0dIWUwc_1/view?usp=drive_link) <br />
You can also directly download the adaptedImage.h5 from [here ](https://drive.google.com/file/d/12VuA-Yv4YcjiszoI3G6eGp9PD3d4QVev/view?usp=drive_link)


![image](https://github.com/davyeu/Font-Recognition-by-CNN/assets/37835891/d64141c1-ee79-4371-9201-2d1789e3992a)
