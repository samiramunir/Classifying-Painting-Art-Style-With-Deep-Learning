# Classifying Paintings by their Art Styles

![](/Media/artstyles.png)



Objective: 
	For this project I attempted to use convoluted neural networks and transfer learning to train a model to be able to classify 		a paintings art style. I used a dataset of paintings found on Kaggle. The details can be found at the following link. 

https://www.kaggle.com/c/painter-by-numbers/data


Process: 

The initial data exploration revealed that not all art styles had enough examples. So I picked  5 art styles that had atleast 1000 samples and that were visually quite different from each other. 



![](/Media/EDA.png)



Engineered a CNN  on top of pretrained model VGG19 at the backend  to train on over 3000 painting images labeled by their art style. 

Conducted hyper parameter tuning using Talos. 

Final model: VGG19  +  4 Dense Layers (Relu) + final layer (Softmax). Achieved test accuracy of 68%.





![](/Media/model.png)

*************************************************************
Project Partner [Yi Shuen Lim](https://github.com/yishuen)
*************************************************************
