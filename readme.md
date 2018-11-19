The wafer images have been downscaled with a factor 3, you need to adjust the provided ground truth accordingly.

# Week 1

## Make scripts to conveniently convert section coordinates between
- provided ground truth
- labelme format (use json library and you probably need to use labelme from the command line to load annotations separately. With the GUI labelme seems to always save the image along with the annotations)
- input/output to implementations of Mask-CNN

## Get one ot the suggested Mask-CNN implementations to run (or one that you find more suitable)

- does it run ok on a laptop ?
- do you need to train [online](https://cloud.google.com/gpu/)?

Play with parameters such as
- train with magnetic parts only
- train with tissue parts only
- train with whole sections
- does it train well with 1, 10, 100, 500 sections in the ground truth ?