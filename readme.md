# Byrd-SAGA
This hub stores the code for paper *Byzantine-Resilient Distributed Finite-Sum Optimization over Networks* (short version) and *Federated Variance-Reduced Stochastic Gradient Descent with Robustness to Byzantine Attacks* (full version, which can be seen in `Full.pdf`). The code should be run in the *jupyter notebook*.

## Environment
- python 3.7.4
- pytorch 1.2.0
- matplotlib 3.1.1

## Construction
The main programs can be found in the following files:
- Byrd_SAGA_torch_LinearRegression.ipynb: The experiment on linear regression.
- Byrd_SAGA_torch_ANN.ipynb: The experiment on neural network.
- draw.ipynb: The script to draw picture.

## Runing
Download the dataset to the file folder `./dataset` and create a file folder named `./cache`. The experiment output will be stored in `./cache`.

## Download dataset
- *ijcnn1/covtype*: [https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/)
- *MNIST*: [http://yann.lecun.com/exdb/mnist/train-images-idx3-ubyte.gz](http://yann.lecun.com/exdb/mnist/train-images-idx3-ubyte.gz)

## Acknowledgement
We would like to thanks to Runhua Wang, SYSU, for helping us to review and improve our code.