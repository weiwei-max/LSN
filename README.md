# Long-term Spatio-temporal Network
This is the implementation of Long-term Spatio-temporal Network for Video Recognition
Now in experimental release, suggestions welcome.
## Paper
Zhenwei Wang, Wei Dong, Bingbing Zhang, and Jianxin Zhang. LSN: Long-term Spatio-temporal Network for Video Recognition.
## Introduction
Though Long short-term memory (LSTM) is widely exploited to process temporal or sequential data, it has attracted too little attention in the current mainstream field of video action recognition. Therefore, this work attempts to model long-term spatio-temporal information of video action based on LSTM, and proposes a novel Long-term Spatio-temporal Network (LSN). The core of LSN is composed of the high-order ConvLSTM (HO-ConvLSTM) module and 2D convolution. More specifically, we adopt HO-ConvLSTM module that consists of an Accumulated Temporary State (ATS) module and a standard ConvLSTM as a bottleneck structure with residual connections, and then insert HO-ConvLSTM into different stages of 2D convolutional neural networks (CNNs). In ATS module, several previous hidden states are combined to one temporary state, and the update of the current hidden state is up to the fusion one. By doing so, the longer temporal correlation of the spatio-temporal features are captured in different spatial resolutions. The experiments on three commonly used video benchmarks demonstrate that our method can achieve performance matching or better than the state-of-the-arts.
## Framework
![]()  
