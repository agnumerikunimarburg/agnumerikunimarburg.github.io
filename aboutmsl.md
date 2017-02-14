---
layout: page
title: About
subtitle: Marburg Software Library
published: true
---

The Marburg Software Library (**MSL**) is a collection of wavelet based c++ algorithms to solve multivariate partial differential equations on bounded domains. THe code realizes several different variants of adaptive wavelet algorithms, that are guaranteed to converge with optimal order. A theoretical background and a lot of additional information can, e.g, be found in "Quellen".
The project was founded in 2002 by Thorsten Raasch and Manuel Werner. Since then it was further developed by a whole bunch of PhD students of the AG Numerik Uni Marburg. From day one the MSL was planned as open source code directed at interested scholars as well as researchers. The aim of this project is twofold: on the one hand it may serve as a source for bachelor/master theses or a numerical practical course. On the other hand interested scientists can use it as a starting point for their own numerical research projects. 
We encourage everyone to contribute to the MSL. Feel free to fork and clone the project and make pull requests if you have ideas for improvements and advancements of the existing code.

The MSL consists of the two branches, master and experimental. We recommend to start with the master branch which is tested a lot and should compile and execute flawlessly. The experimental branch is still under construction, and it is our aim to polish the code there and to transfer it step by step to the master branch. Certainly you can help us here if you like to!   
Inside the branches, the MSL is divided into the different parts MathTL, WaveletTL, FrameTL and Examples. The TL stands for template library indicating the template structure of the code. While MathTL contains some fundamental mathematical tools, such as .. one can find the implementations of wavelet bases on different domains as well as the adaptive schemes in WaveletTL. The folder FrameTL consists of algorithms based on wavelet frames.
Every TL has a subfolder /tests and we recommend to compile the code and execute the files in this folders to get a good impression of how the code is working. In the Examples folder there are implemented versions of the algorithms in CDD1 and CDD2 on the unit interval. For the CDD1 algorithm on the unit interval there is also a graphical user interface (GUI) available. We will extend the GUI to more advanced problems in two dimensions in the near future. 

If you want to try out the MSL you should read the part [How to use](/howtomsl).
