# Codebase for Analysing the Hateful Memes Dataset    

by :- Tarun Teppala

Preface: The code has been tuned to run on a laptop GPU (Nvidia GTX 1650) and is extremely weak and unoptimized

## The following are the objective tasks:

 - A: Object Detection (Bonus Subtask A: Image-only label classifier)
 - B: Caption Impact Assessment
 - C: Classification System Development
 - D: Bonus: Text-only label classifier

The code is organized in a Python Notebook, with modules for Imports, Pytorch classes for Preprocessing and running classification tasks.

## Required libraries:

 - torch
 - torchvision
 - Numpy
 - Pandas
 - easyocr
 - Matplotlib
 - PIL
 - other utility libraries such as os,json, string, enum

## Task Performance

 - Task A: Successfully extracted image features by object detection from the dataset. Plotting frequency and confidence of detected object classes. [Bonus Subtask: Successfully ran a classifier on the image features to obtain results of the classifier; present at the end of code]​

 - Task B: Successfully implemented a method to mask the text captions of the images and observed the difference in how the masking improved confidence of the object detection.​

 - Task C: Created a classification model that could use the image and text features to classify if the meme is hateful or not. The model proved to perform better than random guesses.​

 - Bonus Task D: Successfully ran the classification model with only the text features to find that it could perform comparably to its results from Task C.​

​
