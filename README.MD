# Guide
In order to run the tessaract first do the following
```
sudo apt install tesseract & pip install pytesseract scikit-image  
pip install -U imutils
```
to run, 
```
python readingbooks.py -s <source>
```
The source should be the source of the image that contains the page that you want to read.

what can be source? its either path to image or use webcam ( to use webcam pass 0 or 1 if you 
have an external webcam)

In order to morph the image during image processing(only applicable for images )use -m True (  its false
by default)

```
python readingbooks.py -s test.png -m True
```