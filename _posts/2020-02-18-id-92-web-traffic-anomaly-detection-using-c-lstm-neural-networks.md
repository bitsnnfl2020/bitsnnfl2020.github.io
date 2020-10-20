---
layout: post
author:
  name: 'Paper ID: 92'
  email: bitsnnfl@gmail.com
share: true
title: Web traffic Anomaly Detection using C-LSTM Neural Networks
categories:
- CNN
- LSTM
- Anomaly Detection
tags: []

---
**Abstract** - eb traffic refers to the amount of data that is sent and received by people visiting online websites. Web traffic anomalies represent abnormal changes in time series traffic, and it is important to perform detection quickly and accurately for the efficient operation of complex computer networks systems. In this paper, we propose a C-LSTM neural network for effectively modeling the spatial and temporal information contained in traffic data, which is a one-dimensional time-series signal. We also provide a method for automatically extracting robust features of spatial-temporal information from raw data. Experiments demonstrate that our C-LSTM method can extract more complex features by combining a convolutional neural network (CNN), long short-term memory (LSTM), and deep neural network (DNN). The CNN layer is used to reduce the frequency variation in spatial information; the LSTM layer is suitable for modeling time information, and the DNN layer is used to map data into a more separable space. Our C-LSTM method also achieves nearly perfect anomaly detection performance for web traffic data, even for very similar signals that were previously considered to be very difficult to classify. Finally, the C-LSTM method outperforms other state-of-the-art machine learning techniques on Yahoo’s well-known Webscope S5 dataset, achieving an overall accuracy of 98.6% and recall of 89.7% on the test dataset.

**Paper** - [https://reader.elsevier.com/reader/sd/pii/S0957417418302288?token=EABD67EDB8FE6CD9A10A9159A5C450758A234D2240EAF0480C4A5DB11FCD32C3B4BAC8950729D5178F73E176758F7416](https://reader.elsevier.com/reader/sd/pii/S0957417418302288?token=EABD67EDB8FE6CD9A10A9159A5C450758A234D2240EAF0480C4A5DB11FCD32C3B4BAC8950729D5178F73E176758F7416 "https://reader.elsevier.com/reader/sd/pii/S0957417418302288?token=EABD67EDB8FE6CD9A10A9159A5C450758A234D2240EAF0480C4A5DB11FCD32C3B4BAC8950729D5178F73E176758F7416")

**Dataset -**

* Primary Link - [https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70](https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70 "https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70") (Note - Sign up and agree to the licenses beforehand, as it might take time for them to approve the access)
* Alternate Link - [https://github.com/harris0704/nbaData16-17/tree/master/Yahoo_S5_Data](https://github.com/harris0704/nbaData16-17/tree/master/Yahoo_S5_Data "https://github.com/harris0704/nbaData16-17/tree/master/Yahoo_S5_Data")

**Problem Statement** -

1. Split the data in 70% training and 30% testing set as given in the paper. Perform data preprocessing and clearly report all parameters of the data, eg. number of data samples of various categories in training and testing sets. In the notebook containing the code, clearly show graphs with respect to these.
2. Implement the C-LSTM architecture (table 6) as given in the paper using Keras API of Tensorflow, and train the model for classification of the data as Normal & Abnormal.
3. Report the results providing graphs of cross-entropy loss and accuracy vs. epochs during training, and confusion matrix, precision, recall, F1-score and accuracy on the test set (in the notebook).
4. **Bonus**: Perform Misclassification data analysis (Section 4.2.3) and mention probable reasons for the same.

**Few Resources to Understand Key Concepts -**

1. Understand LSTMs and GRUs - [http://colah.github.io/posts/2015-08-Understanding-LSTMs/](http://colah.github.io/posts/2015-08-Understanding-LSTMs/ "http://colah.github.io/posts/2015-08-Understanding-LSTMs/"), [https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21 "https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21")
2. Understand CNNs - [http://cs231n.github.io/convolutional-networks/](http://cs231n.github.io/convolutional-networks/ "http://cs231n.github.io/convolutional-networks/"), [http://cs231n.github.io/understanding-cnn/](http://cs231n.github.io/understanding-cnn/ "http://cs231n.github.io/understanding-cnn/"), [https://towardsdatascience.com/understanding-cnn-convolutional-neural-network-69fd626ee7d4](https://towardsdatascience.com/understanding-cnn-convolutional-neural-network-69fd626ee7d4 "https://towardsdatascience.com/understanding-cnn-convolutional-neural-network-69fd626ee7d4")
3. Intuitive Explanation of ConvNets - [https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/ "https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/")

(**Note** - These resources are just suggestive and not compulsory to go through. Feel free to explore and understand in your own way)