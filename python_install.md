# Python Installation Step-by-Step

## Python
- Download Python from www.python.org
- Select 3.x & 64bit version
- Python 2.7 will phase out at 2020

## Update Pip
- pip3 install --upgrade pip

## Download key libraries
- [UCI](http://www.lfd.uci.edu/~gohlke/pythonlibs/)
- Numpy+mkl (www.numpy.org)
- Scipy (www.scipy.org)

## Install Jupyter Notebook
- [Jupyter](www.jupyter.org)
- pip3 install jupyter
- pip3 install jupyter_contrib_nbextensions

## Install other key libraries: Matplotlib, Pandas, Seaborn
- pip3 install matplotlib
- pip3 install pandas
- pip3 install seaborn
## Install image processing libraries: OpenCV, Pillow
- pip3 install opencv-python (www.opencv.org)
- pip3 install pillow
## Install Machine Learning packages
- pip3 install scikit-learn (from UCI)
- pip3 install tensorflow (from UCI)
- pip3 install h5py (from UCI)
- pip3 install Cython
- pip3 install keras
- pip3 install Theano
- Pip3 install xgboost (from UCI)
- Other (caffe, mxnet)
## PEP8
- pip3 install pep8 (part of spyder)
- pip3 install pylint (part of spyder)
- pip3 install flake8
- pip3 install autopep8
- pip3 install pyflake (part of spyder)
## Imread from scipy
- from scipy.ndimage import imread
## Install spyder (Python IDE)
- pip3 install PyQt5 (need to install it first)
- pip3 install spyder
## Jupyter-contrib extensions:
- !pip3 install https://github.com/ipython-contrib/jupyter_contrib_nbextensions/tarball/master
- !pip3 install jupyter_nbextensions_configurator
- !jupyter contrib nbextension install --user
- !jupyter nbextensions_configurator enable --user
## Compile
- Python -m compileall
- Python -m py_compile filename
