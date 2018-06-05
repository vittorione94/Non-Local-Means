# Non local Means


## Intro

In this project I implemented a non-local mean filtering in a naive way and using integral images. These two methods 
are both explained in the papers : 

1. paper1
2. paper2

## Description

The non local-means algorithm is used to remove noise from an image. We have in input three things: 
1. The image we want to denoise  
2. A kernel of size k x k
3. A window of size w x w

for each pixel in the image (that we are going to denoise) we center the window around it, usually the window is reasonably big but of course not as big as the 
entire image, then for each pixel in the window we 

## How to use the code  
