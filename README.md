# Exercises for the Inverse Problems and Deep Learning School in Hanoi, Vietnam 

Here you will find the course exercises as well as the solutions. I will upload the exercises gradually so using it as a Git repository is a good idea, otherwise you can download everyday the updated .zip with all the files.


## Installation instructions

### 1) Create folder for the exercises 
If you are using Git, then this happens automatically, otherwise download a .zip file with the content of the repository and uncompress it. Be careful that you don't loose your own solutions when updating the folder!

### 2) Install Python

For the exercises we are going to use Python (Miniconda distribution).

The installer files for all platforms (Windows, Lunix, Mac) can be found in:

[https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

Please download the appropiate installer and run it.

 - If your computer has a 64-bit operating system (most likely) select the *64-bit installer* for *Python 3.7*.

 - If your system has a 32-bit operating system (unlikely) you will need to install the *32-bit installer* for *Python 3.7*.
 
 - If you get asked if you want to add the Miniconda directory to the `PATH` select yes.
 
**UPDATE**
One of the required packages *tensorflow* will only run with a 64-bit operating system.
 
**UPDATE**
Please confirm that you have successfully installed Miniconda by opening a console and typing `conda`. If an error appears then Conda was not added to the `PATH`. You have to search for the *Anaconda Promt* terminal and open it. Then you have to change the directory the terminal is pointing to, using for example `cd local_folder\local_folder2`, to the directory that contains the exercises.
 
### 3) Install required packages

The list of required packages is contained in the file [requirements.txt](/requirements.txt). To install all of them open a console on the folder where you have the file and type `pip install -r requirements.txt`.

### 4) Run Jupyter Notebook
When everything is installed open a terminal on the exercises folder and run `jupyter notebook`.


## Documentation

Whenever you are programming in a new language it is really important to use the documentation to find out what methods are available on each package. 

These are some of the package documentations that might be helpful for you in this course:
 - [**numpy**](http://www.numpy.org/): for scientific computing (vectors and matrices operations)
 - [**numpy.linalg**](https://docs.scipy.org/doc/numpy/reference/routines.linalg.html): for linear algebra methods.
 - [**skimage**](http://scikit-image.org/docs): for image processing tasks (here you can find the *Radon* transform)
 - [**sklearn**](https://scikit-learn.org): for machine learning tasks, includes example datasets and many usefull functions for doing machine learning.
 - [**keras**](https://keras.io/): friendly common interface for creating neural networks using different backends, such as tensorflow and theano.
 

## Exercise notebooks

 - [Introduction](https://github.com/otero-bremen/hanoi-school/blob/master/introduction.ipynb) <a href="https://raw.githubusercontent.com/otero-bremen/hanoi-school/master/introduction.ipynb" download>[Download]</a> Introduction to python and examples for the NumPy and Matplotlib packages.
 - [Inverse Problems (Part 1)](https://github.com/otero-bremen/hanoi-school/blob/master/inverse_problems_1.ipynb) <a href="https://raw.githubusercontent.com/otero-bremen/hanoi-school/master/inverse_problems_1.ipynb" download>[Download]</a> Analytic methods for solving Inverse Problems.
 - [Neural Networks (Part 1)](https://github.com/otero-bremen/hanoi-school/blob/master/neural_networks_1.ipynb) <a href="https://raw.githubusercontent.com/otero-bremen/hanoi-school/master/neural_networks_1.ipynb" download>[Download]</a> Introduction to Neural Networks. Regression and Binary Classification.
 - [Neural Networks and Inverse Problems (Part 1)](https://github.com/otero-bremen/hanoi-school/blob/master/neural_networks_and_inverse_problems_1.ipynb) <a href="https://raw.githubusercontent.com/otero-bremen/hanoi-school/master/neural_networks_and_inverse_problems_1.ipynb" download>[Download]</a> Example of the 2x2 matrices.
 - [Neural Networks (Part 2)](https://github.com/otero-bremen/hanoi-school/blob/master/neural_networks_2.ipynb) <a href="https://raw.githubusercontent.com/otero-bremen/hanoi-school/master/neural_networks_2.ipynb" download>[Download]</a> Convolutional Neural Networks for classifying digits (MNIST).
 - [Inverse Problems (Part 2)](https://github.com/otero-bremen/hanoi-school/blob/master/inverse_problems_2.ipynb) <a href="https://raw.githubusercontent.com/otero-bremen/hanoi-school/master/inverse_problems_2.ipynb" download>[Download]</a> Computarized Tomography.
 - [Neural Networks and Inverse Problems (Part 2)](https://github.com/otero-bremen/hanoi-school/blob/master/neural_networks_and_inverse_problems_2.ipynb) <a href="https://raw.githubusercontent.com/otero-bremen/hanoi-school/master/neural_networks_and_inverse_problems_2.ipynb" download>[Download]</a> Learned postprocessing for Computarized Tomography
 - [Inverse Problems (Part 3)](https://github.com/otero-bremen/hanoi-school/blob/master/inverse_problems_3.ipynb) <a href="https://raw.githubusercontent.com/otero-bremen/hanoi-school/master/inverse_problems_3.ipynb" download>[Download]</a> Iterative Soft Thresholding Algorithm (ISTA).

Play online with Neural Networks for binary classification at [http://playground.tensorflow.org](http://playground.tensorflow.org)
