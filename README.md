# Image_to_cartoon
Pick an image and create a cartoon image from that.

Here we have used two methods:
1. Color_quantization
2. Edge_Mask

## Color_Quantization
https://www.analyticsvidhya.com/blog/2021/07/colour-quantization-using-k-means-clustering-and-opencv/

Colour quantization is the method of lessening the abundance of different colours applied in an image. We may be required to produce this sort of compression to render an image in media supporting only a restricted number of shades (ordinarily due to memory restraints).

Certainly, all compressions come with a price. In this example, the resulting picture may deviate too much from the primary one. Therefore, the colour quantization aims to achieve a compressed copy comparable to the real one. The essential constituent for accomplishing this is choosing the colour palette by picking the colours that compile the initial image.

The most popular procedures overcome the obstacle of colour quantization into a clustering problem of features where each feature describes the colour of a pixel. It consists of building the palette by picking a characteristic topic for all clusters. Following that, the compression remaps all the values into their cluster representative. As you may imagine, the resulting palette deeply depends on the colour spectrum and distance metric applied.

For more info please follow the link.

## Edge_Mask

Edges are characterized by sudden changes in pixel intensity. To detect edges, we need to go looking for such changes in the neighboring pixels.

https://learnopencv.com/edge-detection-using-opencv/

For more info please follow the link.
