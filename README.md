# colours-clustering
clustering the colors of an image with KMeans algorithm.

I choice the following image because it painted with separate colors and its clusters is more readable.

<img src="Four_color_world_map.png" style="width:50%" />

## The project summary
First the all, i read the image and after that, since the i read the image with `opencv` the channel is BGR, so i convert BGR to RGB because i showed the image with `matplotlib`.
i choiced matplotlib for showing image inside the jupyter notebook, by contract Opencv show the image in a seperate window.

after i againe convert the image channel to `HSV'
