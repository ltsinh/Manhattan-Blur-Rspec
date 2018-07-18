## Manhattan Distance Image Blur

Given an image, we want to build a method to blur the image, however instead of only blurring images that are within 1 pixel, we want to specify how far to blur pixels that are within a Manhattan Distance of what is specified. In the previous assignment we built a method that will produce the blurring with a Manhattan Distance of 1. Build the method def blur(distance) that will implement a blurring of the Manhattan distance specified.

In short: you want to find all 1's and turn any pixels that can be reached by making n moves or less using only left, right, up or down from the starting point.