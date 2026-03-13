
Tree-Car-Classifier



The project develops a model that can successfully distinguish between images of trees and cars. 
## Dataset 

The Dataset consists of:

A) 90 Images of cars from Kerala obtained by using google Earth's Street view feature and 10 camera images sent by a Friend.

B) 100 images of cars from Stirling using Google Earth's street view feature. 

C) 100 Images of trees clicked using a camera from Kerala by 2 people who has been acknowledged in the final report. 

D) 100 Images of trees taken by myself at Stirling 

The 
Note: The car images have been taken from the first ITNPAI1 asssignmnet after prior permission.

The Co-ordinates have been provided in the dataset folder in a csv file and also mentioned below:

Kerala: 10.1632° N, 76.6413° E

Stirling: 56.1165° N, 3.9369° W

The link to the origin from where the car pictures were obtained is here below:

Stirling:
https://earth.google.com/web/search/Stirling/@56.11150138,-3.92887975,14.23789269a,2630.52031595d,35y,12.91185296h,0t,0r/data=CnMaSRJDCiUweDQ4ODg1N2Q3M2M0Mzc4MzE6MHhmYmYwMWYzNzAyZDU3NmFkGe3eQDfqDkxAIXA4mPLGfg_AKghTdGlybGluZxgBIAEiJgokCYtrRh-42kpAEWAdYci6b0hAGUy3QBS2wCLAIdTpo4YezyrA

Kerala: https://earth.google.com/web/search/kerala/@10.54457447,76.13784294,14.89259514a,1463785.18620035d,35y,0h,0t,0r/data=CnEaRxJBCiUweDNiMDgxMmZmZDQ5Y2Y1NWI6MHg2NGJkOTBmYmVkMzg3Yzk5GcaD0ryIUyRAIXf3W5YKKVNAKgZrZXJhbGEYAiABIiYKJAk5rqMW6BNMQBFYdwjSdwpMQBlkC6KLtJYOwCFPzm9SJjkQwA




## Codes

The Dataloader consists of mounting the drive to colab, preprocessing the Images with Data augmentation techinques and creating datagenerators from the directory. 

A Sequential model was used in this classification task with the help of tensorflow which the most widely used deep learning framework and has power and flexible API’s such as Keras, that make it easy to define, train, and evaluate deep learning models.
The model was compiled with Binary crossentrpy loss, 'adam' optimizer and accuracy metrics.

The precision, recall and accuracy was calculated and the Loss and Accuracy was plotted. 

Finally the model had run predictions using the test data. 

