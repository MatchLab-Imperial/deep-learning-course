# Deep Learning Course
Welcome! Here we will upload the different tutorials for the Deep Learning course. 
We will use Python and [Jupyter Notebook](https://jupyter.org/), and [Keras](https://keras.io/) as the deep learning framework.
Also, the tutorials use [Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb), which is a free Jupyter notebook environment that runs in the cloud. 

Each of the notebooks contains this image


<p align="center">
<img src ="https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" />
</p>

which when clicked takes you to the Colaboratory website. 

Colaboratory provides free GPU, so you can modify part of the tutorials and retrain the models to test your modifications. Specifically, you get 12 hours of continuous access to a k80 GPU. When those 12 hours are over, you can connect to another machine. This [Notebook](https://colab.research.google.com/notebooks/gpu.ipynb#scrollTo=3IEVK-KFxi5Z) shows a comparison of the CPU vs GPU speed up in Colaboratory. The Hardware accelerator can be selected in Edit->Notebook Settings. There is also the option of using Tensor Processor Units (TPUs), but the tutorials will only use the GPU. Here is an [example notebook](https://colab.research.google.com/notebooks/tpu.ipynb) using TPUs.   

We will update the repository during the course with new tutorials.

## Links to the notebooks
Sometimes the notebooks do not render correctly in GitHub. You can access directly the notebook in the Colab environment using the following links.
### Week 1
  * [Python part 1](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/01_part1_Python.ipynb)
  * [Python part 2](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/01_part2_Python.ipynb)
  
  [18/01/21] Added new section about downloading data from Colab and also saving data to Google Drive.
  * [Keras](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/01_part3_Keras.ipynb)
  
### Week 2
[25.01.2021] Task 1: 1D-NN total number of epochs changed from 10 to 20.

[01.02.2021] Changed nomenclature. Note that in this tutorial, we use test data as our validation set. 

[01.02.2021] Task 2: Study training and validation curves vs the number of training <s>iterations</s> epochs
  * [Introduction to CNNs](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/02_CNN_Introduction.ipynb)

### Week 3
[01.02.2021] Clarification of data splits in Task 1.
[26.02.2021] Changed two "best validation results" to "best validation accuracy" in Task 1.
  * [Network Training](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/03_Network_Training.ipynb)
  
### Week 4
[09.02.2021] Report training <s>loss</s> and validation accuracy curves.

[17.02.2021] Added restore_best_weights=True to EarlyStopping.

[19.02.2021] Corrected UNet definition.
  * [Common CNN Architectures](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/04_Common_CNN_architectures.ipynb)

### Week 5
[16.02.2021] Changed x_test to x_test_char and seq_length to seq_char_length in two lines of Task 3

[24.02.2021] Task 1 rephrasing

  * [RNN](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/05_RNN.ipynb)

### Week 6
  * [Autoencoders](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/06_Autoencoders.ipynb)

### Week 7
[08.03.2021] argmin to argmax in VAE equation
  * [VAE-GAN](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/07_VAE_GAN.ipynb)

### Week 8
  * [RL](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/08_RL.ipynb)


