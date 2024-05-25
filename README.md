
## Set up Process 🐱‍💻
Since i am working on Vscode here are the tools i used 

* Python 3.10.11 : https://www.python.org/downloads/release/python-31011/
* Anaconda : https://www.anaconda.com/download/success (check documentation if needed)
* VScode : https://code.visualstudio.com/download 
* VScode extentsion : https://marketplace.visualstudio.com/items?itemName=ms-python.python
* Tensorflow CPU / GPU : https://www.tensorflow.org/install/source_windows
* Tensorflow Hub : https://www.tensorflow.org/hub/installation
* Cuda and Cudnn :  https://www.tensorflow.org/install/source_windows ( we will work through it on terminal )

## ⚠️ check if your GPU is suitable you can spare youself in using colab but if you want it in vscode follow this doumentation 
## I AM NOT RESPOSNIPLE FOR YOUR LAPTOP'S DEATH
## ⚠️ GPU wont be recognized by anything above than 2.10 


# Terminal Screenshots !! 
Since we are using Conda in the command line we need this terminal ( for easier diagnoses ) 
<img src ="images/Anaconda Terminal.png"/>

# Change to the path of the folder that you have your data in 
use cd command (change directory) 
<img src ="images/cd file directory terminal.png"/>



# Installing the Python via conda command `Proceed Y/N is there  `
Since we are using Conda in the command line we need this terminal ( for easier diagnoses ) 
<img src ="images/conda creation.png"/>



# Conda sucess image! 
Here is an image to show what you should see in the end 
<img src ="images/conda sucess.png"/>



# Activate your Conda 
<img src ="images\activate conda.png"/>




# Get your Cuda  Toolkit and cudnn ( CUDA for neural networks ) ready using this command 
<img src ="images/cuda tools.png"/>



# Cuda Command result pt1
<img src ="images\cuda part 1.png"/>




# Cuda Command result pt2
<img src ="images\cuda part 2.png"/>




# Intall Tensorflow 2.11
<img src ="images\install tensorflow 2.11.png"/>


 # install Tensorflow hub 
 i had to reninstall Tensorflow again cause the version got updated automatically so downgrade it 
 <img src ="images\tensorhub.png"/>


# In case your Tensorflow got updated to 2.16 downgrade it using this command and use `pip list` to show installed versions and then install the 2.10 version again
<img src ="images\tensorflow downgrade.png"/>

<img src ="images\downgrade check.png"/>



# Command success criteria
<img src ="images\command sucess criteria.png"/>



# Now run python to ensure that your tensorGPU works !
<img src ="images\python run.png"/>



# Tenforflow gpu sucess criteria 

<img src ="images\Gpu sucess.png"/>



# VScode Image 
open the folder and this will show automatically 
<img src ="images\vsode first image.png"/>


# Choose the python environment 
<img src ="images\python environment.png"/>


# Press `Shift + Enter ` To run the cell and here is the result 
<img src ="images\GPU vscode result.png"/>







