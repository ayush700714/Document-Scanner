# Document Scanner

![alt text](https://github.com/ayush700714/Document-Scanner/blob/master/project.png?raw=true)

A simple document scanner using opencv and how we can save these images by pressing just a button on the keyboard. It is simple and covers the core principals of opencv. 

The pipeline of the image is as follows:

OriginalImage    ->   GrayScaleImage  ->      EdgeDetector  ->     ContoursDetection  ->     SelectionOf BiggestContour  ->      Warp Prespective(Colored Image)  ->    Adaptive Thresholding(Scanned Document)   ->      Additional functonality of saving the document to a folder by clicking 's' on keyboard
