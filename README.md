# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2021

+ Team 2 Members:
	+ Chen, Xueying xc2578@columbia.edu
	+ Cheung, Corwin cc4671@columbia.edu
	+ Harvey, Dan dyh2111@columbia.edu
	+ Park, Matthew msp2178@columbia.edu
	+ Wang, Wanxin ww2581@columbia.edu
	+ Yorulmaz, Egem ey2300@columbia.edu

 The presenter is Dan Harvey.

+ Project summary:  his project aims to develop an image classification algorithm for CIFAR10 like images that improves upon the baseline logistic regression model provided in the starter code.  Our Model I used a convolutional neural network via the Keras/TensorFlow Library, while our Model II aimed to improve upon the Model I by enhancing the noisy labels through weakly supervised learning.

	
**Contribution statement**: All team members contributed to the planning and brainstorming sessions.  Corwin researched the label cleaning network and differences between using noisy and clean labels, and researched findings from the inoue paper and also tested the baseline model and tensorflow CNN model 1.  Egem researched Keras/Tensorflow models and provided annotated documentation on tutorials using these models. Also researched Label Cleaning from Inoue paper for part 2.Xueying researched and worked on a Pytorch model,  and tested the CNN models by using “dropout”, and preparing the presentation.  Dan researched and tested various filter performance on the baseline model, worked on developing a Pytorch model, and contributed to the Model testing functions, and prepared the final presentation and presented. Wanxing worked on research, debugging the pytorch model, and developed the final working tensorflow CNN model I and improved model II, and prepared documentation for the models.  All team members approve our work presented in this GitHub repository including this contribution statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
