# Combination of Python and painting：Van gogh's Stevens School


[![python3.6](https://img.shields.io/badge/python-3.6-brightgreen.svg)](https://www.python.org/downloads/release/python-368/)

![Keras](https://github.com/hockercobb/myEE551project/blob/master/Keras.png) 

[![theory application]](https://arxiv.org/abs/1508.06576)




## Introduction
This is my EE551 python individual project | Author: HAO CAO

## Purposals
As a beginner python learner, it would be interesting to combine the program with my hobbie: painting.Van gogh is my idol, his painting named The Starry Night is my favourite, we cannot paint a mastwepiece like this, but maybe we can creat other pieces with the help of Python! It's amazing!

## Features
- [x] Configure the running environment using the VGG16 model
- [x] Build style transfer platform with keras
- [x] deep learning algorithm
- [x] Let the computer learn the input image style
- [x] Style is digitized by deep learning algorithm
- [x] The target image was processed iteratively to obtain similar style images



## NEED TO TODO
- [ ] Installate some dependent libraries with Anaconda
- [ ] Configure the operating environment
- [ ] Code designing about dimensions of the generated picture and util function to convert a tensor into a valid image.
- [ ] Run the program on Anaconda and input the run statement, get what we want.

## Author

* **HAO CAO**
## Procedure
### Installate some dependent libraries with Anaconda
pip install keras
pip install h5py
pip install numpy
pip install scipy
pip install tensorflow
pip install matplotlib
pip install Pillow

### Configure the operating environment
download the VGG16 model from Internet

### Writing code
please refer to neural_style_transfer.py.

### Run the program on Anaconda and input the run statement
run the program on the Anaconda and input:
python neural_style_transfer.py ./stevens.jpg ./starry_night.jpg ./stevens_t

### Introduce pictures
Introduce pictures and put them and neural_style_transfer.py.in the same folder.


## Outcome Description
This is Van gogh's The Starry Night:

![](https://github.com/hockercobb/myEE551project/blob/master/starry_night.jpg)

This is our stevens School:

![](https://github.com/hockercobb/myEE551project/blob/master/stevens.jpg)

After 10 times iteration：
we got them:

![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_0.png)
![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_1.png)
![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_2.png)
![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_3.png)
![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_4.png)
![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_5.png)
![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_6.png)
![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_7.png)
![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_8.png)
![](https://github.com/hockercobb/myEE551project/blob/master/stevens_t_at_iteration_9.png)










