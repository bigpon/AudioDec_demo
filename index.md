---
layout: default
---
This page is the demo of "Quasi-periodic parallel WaveGAN vocoder: a non-autoregressive pitch-dependent dilated convolution model for parametric speech generation" [[paper](https://ieeexplore.ieee.org/document/10096509)] [[code](https://github.com/facebookresearch/AudioDec)]

## **Abstract**  
<p align="justify"> A good audio codec for live applications such as telecommunication is characterized by three key properties: (1) compression, i.e. the bitrate that is required to transmit the signal should be as low as possible; (2) latency, i.e. encoding and decoding the signal needs to be fast enough to enable communication without or with only minimal noticeable delay; and (3) reconstruction quality of the signal. In this work, we propose an open-source, streamable, and real-time neural audio codec that achieves strong performance along all three axes: it can reconstruct highly natural sounding 48 kHz speech signals while operating at only 12 kbps and running with less than 6 ms (GPU)/10 ms (CPU) latency. An efficient training paradigm is also demonstrated for developing such neural audio codecs for real-world scenarios. </p>


## **Architecture**  
<center><img src="res/figure/audiodec.svg" style="display:block;width:500px;height:370px"></center>  

  
## **Demo Sounds**
<p align="justify"> Due to the legal issue, we cannot share the results of VCTK or LibriTTS, but we recommend you try our <a href="https://github.com/facebookresearch/AudioDec">open-source code</a> to get the results. We are trying to find a suitable corpus without any legal concerns, and we will release the results as soon as possible. </p>

## **Speech Quality Measurments** 
<center><img src="res/figure/Quality.svg" ></center>  

## **Latency Analysis (ms)** 
- GPU: NVIDIA GeForce RTX3090
<center><img src="res/figure/GPU.svg" ></center>
- CPU: AMD Ryzen Threadripper 3970X w/ 4 threads
<center><img src="res/figure/CPU.svg" ></center>
  
<br /> 

<br /> 
[Home](https://bigpon.github.io/)

<br />  
<br />  