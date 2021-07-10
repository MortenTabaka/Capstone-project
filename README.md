# Getting started with TensorFlow 2 - Capstone project

  Work presents image classification of the SVHM dataset. RGB colored images of size 32x32 pixels, represents clipped digits of real world house-number photos in various resolution. There are two neural network models used. MDL and more accurate CNN, destined for image categorization. Both models were trained on set containing 73257 images and validation set as 15% of those images. Models were evaluated using test set, which consists of 26023 samples. 
  
To run the project, first download dataset from: **http://ufldl.stanford.edu/housenumbers/**.
Next open Colab_notebook.ipynb file in Jupter or Colab and after modification of the images' path, execute the code.  

Environment requirements: 
* Jupyter/Colab
* Python 3.x
* Tensorflow 2.2.0
* Libraries:
  * Matplotlib
  * NumPy
  * Pandas
  * SciPy

  Dataset reference: Yuval Netzer, Tao Wang, Adam Coates, Alessandro Bissacco, Bo Wu, Andrew Y. Ng Reading Digits in Natural Images with Unsupervised Feature Learning NIPS Workshop on Deep Learning and Unsupervised Feature Learning 2011. (PDF) http://ufldl.stanford.edu/housenumbers
