I will upload my project soon

# FSA-Net-SSR-Net_MD-MXNet
Realization a part of FSA-Net by MXNet, which is used on detect human face's 3 Euler angles.FSA net project is a model for face angle calculation. 
The network is based on the improvement of SSR net network (age measurement). In the process of improvement, several different versions have 
been formed. The author's network implementation is based on keras + tensorflow. As the project needs Caffe or mxnet version model, two 
attempts have been made, one is to convert keras model to Caffe, the other is to retrain an mxnet version of FSA. Record the latter here. Select 
the simple version of FSA to reproduce, that is, the version closest to its predecessor, SSR. Because the effect of different versions is not very different, 
but the simple version is very convenient to reproduce. The implementation of mxnet network mainly refers to the FSA model, SSR age detection 
mxnet and some mxnet basic applications.

You can see the introduction of each file in readme.txt. It's relatively simple. I believe you can easily understand how to operate it.

# train:
python train_fsa_angle.py

# test:
python test_fsa_angle.py

# detailed process:
This link describes the specific implementation process of the project. It is a very detailed process I wrote. It is in Chinese:
https://blog.csdn.net/pc9803/article/details/102603689#commentsedit

# Reference:
https://github.com/shamangary/FSA-Net                                                                                                   
https://github.com/wayen820/gender_age_estimation_mxnet
https://blog.csdn.net/scythe666/article/details/83058528


