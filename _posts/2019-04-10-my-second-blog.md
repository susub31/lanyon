---
layout: post
title: What is Transfer Learning?
---

One of the advanced techniques you hear in any image classification or NLP task is "Transfer Learning".  Well, what is it?  Let's find out:

> What is Transfer Learning?

Well, as the name implies, "Transfer Learning" refers to a learning gained in one task or usecase that can be repurposed for another.  When it comes to any neural network or Deep Learning task, it comes down to how well the weights are obtained through gradient descent and back propagation to learn the non-linearities in the data that it sees.  And, the deeper the neural network architecture is, the better it has shown to perform.  Some of the architectures that have produced great results using ImageNet dataset are AlexNet, LeNet, ResNet, VGG etc.  All of these architectures are several layers deep and so, it takes several hours to train the model.  Through Transfer Learning, one of the approaches is to use a pre-trained model.  What we are essentially trying to do is to freeze up to a certain number of layers and use the weights at that point to feed into our final layers, where we will be training specific to our own dataset.  



> Why is Transfer Learning gaining so much popularity?

Through Transfer Learning techniques, people have been able to apply the learnings from huge architectures on their own dataset and have shown to produce great results.  It also helps cut down in terms of training time and costs and yet have the benefit from huge successful architectures.  


> Where do I start?  

NVIDIA offers a ["Transfer Learning Toolkit"](https://developer.nvidia.com/transfer-learning-toolkit), that is ideal for deep learning application tasks, thus enabling Data Scientists to achieve faster and efficient workflow.  Google recently released their ["Tensorflow Hub"](https://www.tensorflow.org/hub), which is essentially a library for reusing pre-built machine learning models.  

One of the architectures that has gained popularity in the field of Natural Language Processing is the Transformer architecture on which BERT (Bidirectional Encoder Representations from Transformers) is based on.  This technique generates embeddings for a word, based on the context in which the word appears.  In one of my recent NLP projects, using BERT's contextual embeddings, we were able to show that a model is able to tag as high risk for heart disease when there is a mention of BP above a certain level, say 190/140 and not to tag when the value is say, 120/80.  The transformer architecture has shown to have superior performance in modeling long-term dependencies in the text compared to RNN or LSTM.  Google offers a Collab environment for you to play with BERT fine-tuning and TPU.  Here is a link to [my notebook on Google Collab](https://github.com/susub31/DL_ON_EDGE).  Google's collab is a great place to get started! 


