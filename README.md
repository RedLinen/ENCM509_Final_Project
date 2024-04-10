# ENCM509_Final_Project

This repository contains the image data used to train the neural nets for our ENCM509 final project, the results generated from testing, and all code used for training and evaluation of the neural nets. If you wish to test this code, please do the following:

1.	Clone this repository to your computer.

2.	Open “julias depth forge.ipynb” and run all cells. The first part of this Notebook contains the code to reorganize the picture data stored in “Apocrypha V1 Elana\Cam Data Folders” into test and validation sets, convert it from pickle files to .jpg files, and store it in the “Data Converted to JPG” folder. The second part of this Notebook loads colorized depth image data and uses it to train and save a neural net.


3.	Open “julias RGB forge.ipynb” and run all cells. This Notebook loads RGB image data and uses it to train and save another neural net.

4.	Open “Analysis.ipynb” and run all cells. This will use the test results stored in “Apocrypha V2 Kate (joshua)\Cam Data Folders” and “ENCM509_Final_Project\Apocrypha V2 Kate (Sarim Data) )\Cam Data Folders” to analyze the performance of the neural nets.
