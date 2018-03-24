# Carvana Image Masking Challenge

This is a project for the Kaggle competition "Carvana Image Masking Challenge". The basic idea of this competition is to automatically identify the boundaries of the car in an image.

#Stage One: Search for Useful Ideas

## 1. Baseline
> As there is only one type of object in this task, the basic idea is using U-net structure for the segmentation. 


## 2. Possible optimazations

> (1) Data argumentation: Rotation, Shift, Adding noise, Scale

> (2) Multi-Scale features: Use the idea of DenseNet and Feature Pyramid Net to use more information of features.

> (3) Add densenet structure at the top to get more precise result at the edge.

> (4) Add other blocks to further improve the result: inception block, dense block, sen block, capsule block, Diation Convolution.

## 3. Get more ideas
> (1) Read papers about optimization of U-net.

> (2) Read the discussion and kernals of this competition on Kaggle.

#Stage Two: Ensenble Useful Ideas

## 1. Useful Ideas Summary

> (1) Use Diation Convolution in the middle layer.

> (2) Ensemble results of different argumentation pictures

> (3) Use another U-net to train along the edges of the predictions of U-net using small pathes of the original image. The ultimate implementation of this idea is to combine these two U-net into one model and train a end-to-end model.

## 2. To do list
> (1) 

 
