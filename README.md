# FacialRecognition
  This is practice of facial recognition by tensorflow
  
  I try to do transfer learning to make a small step for this repos. 
  
  Transfer learning is a good way for programmer to do the implementation.
  
# Scenario
![img](https://miro.medium.com/max/868/1*6xp-IY-M8lEEEN0UuUBq0w.jpeg)

# Reference
[kaggle::code](https://www.kaggle.com/gauravsharma99/facial-emotion-recognition)<br>

# Trouble-Shooting
* [how to run ipynb files in vscode?](https://towardsdatascience.com/jupyter-notebook-in-visual-studio-code-3fc21a36fe43)<br>

* [how to link your ipynb on PC using your own google colab?](https://stackoverflow.com/questions/59508225/is-it-possible-to-connect-vscode-on-a-local-machine-with-google-colab-the-fre)
* [A simple keras model on my laptop webcam](https://medium.com/@jinilcs/a-simple-keras-model-on-my-laptop-webcam-dda77521e6a0)

* [PIL.Image，OpenCV，Numpy Image格式互相轉換](https://ithelp.ithome.com.tw/articles/10230274)

* [simple-sample-code](https://github.com/DC-Cheng/webcam-model/blob/master/detect_me.py)

* [How to predict new samples with your TensorFlow / Keras model?](https://www.machinecurve.com/index.php/2020/02/21/how-to-predict-new-samples-with-your-keras-model/)

* [webcam opencv-python sample code](https://www.codegrepper.com/code-examples/python/opencv+webcam+test+python)

* [transfer learning from pre-trained models](
https://towardsdatascience.com/transfer-learning-from-pre-trained-models-f2393f124751)

* [predict or predict_classes](https://blog.csdn.net/zds13257177985/article/details/80638384)

# Classicial Models
* AlexNet
* VGG16
* GoogLeNet / InceptionV1
* Resnet50

# Reference Models
** DCNN **
- conv2d_1
- batchnorm_1
- conv2d_2
- batchnorm_2
- maxpool2d_1
- dropout_1
- conv2d_3
- batchnorm_3
- batchnorm_4
- maxpool2d_2
- dropout_2
- conv2d_5
- batchnorm_5
- conv2d_6
- batchnorm_6
- maxpool2d_3
- dropout_3 
-*flatten
- dense_1, elu
- batchnorm_7
- dropout_4
- dense_out, softmax
-*compile()


# Result
  
  ![result-1](https://github.com/DC-Cheng/AI_facial_recognition/blob/master/fer-result-1.png?raw=true)
  ![result-2](https://github.com/DC-Cheng/AI_facial_recognition/blob/master/fer-result-2.png?raw=true)
  ![result-3](https://github.com/DC-Cheng/AI_facial_recognition/blob/master/fer-result-3.png?raw=true)
