## Basics you need to know about imageprocessing in python

n computer science, Image processing is a process of enhancing the image or extracting some information from the image.

In Python, there are two main libraries that we can benefit from for Image processing tasks.

1 - Pillow which is a fork from PIL (Python Imaging Library)
2- OpenCV (Open Source Computer Vision)

I found out for basic image processing tasks working with Pillow is easier.

An image is a matrix of pixels. In grayscale images, each pixel can be presented with one value. The value shows the intensity of the pixel. In another word, it shows how dark or bright the pixel is. Depends on the library you are using the value can be a decimal number between 0 and 1 or a number between 0 and 255.

![alt text](https://1.bp.blogspot.com/-v9M3NxvaGmg/WzLnjm8U1nI/AAAAAAAACY4/-TSRWDbSmawzGPrztxcanZx21MFw7fMLACLcBGAs/s640/Grayscaleimages.PNG "grayscale image")

In the coloured images, the pixel value is a three column array. PIL uses RGB order and Open CV uses BGR order. Each column represents the value between 0 and 255.
![alt text](https://1.bp.blogspot.com/-vbftQ6Nybog/WzLnjiGp3cI/AAAAAAAACY0/mkbcEX8-nKggLXVRUA2wj3pG0DW_8eTkACLcBGAs/s640/Colouredimages.PNG "coloured image")


You can read the full blog post [here](http://azadehkhojandi.blogspot.com/2018/06/image-processing-in-python.html). 
