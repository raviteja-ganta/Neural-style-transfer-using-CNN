# Neural-style-transfer-using-CNN
This repo contains all project files for Neural style transfer using CNN's

what is style transfer between images? I will try to explain it with the example below

We have content image which is a stretch of buildings across a river. We also have a style image which is a painting.
Main idea behind style transfer is to transfer the 'style' of style image to the content image so that the target images looks 
like buildings and river painted in style of artwork(style image). We can clearly see that content is preserved but looks like 
buildings and water are painted.

To do this we just need to extract content from content image, style from style image and combined these two to get our target image. 
But before that lets understand what exactly content and style of an image are.

##Content of an Image: 
Content can be thought as objects and arrangements in an image. In our current case, content is literally content 
in the image with out taking in to account texture and color of pixels. So in our above examples content is just houses, water and grass 
irrespective of colors.

##Style of an Image: 
We can think of style as texture, colors of pixels. At same time it doesn't care about actual arrangement and 
identity of different objects in that image.
