## Image processing 
In this repo, images are analysed with skimage (a python package). The images are firstly segmented to create separate regions according to their identity for easier analysis. In segmentation, histograms for the images are plotted  to find some patterns in the pixel values. Also, Thresholding step is performed during segmentation.
Apart from segmentation, images of barcodes and QR-codes are also processed to retrieve the infromation (URLs) behind those codes by using pyzbar package. 
Install required packages from requirements.txt file  
`pip install -r requirements.txt` 
Python version 3.8.8
