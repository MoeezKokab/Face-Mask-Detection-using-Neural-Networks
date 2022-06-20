# Face-Mask-Detection-using-Neural-Networks
i try 4 diiferent model to find best Accuracy

language => python <br>
dataset => https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset <br>
Need to install  => Numpy (np) , Matplotlib (plt) , Tesnsorflow(tf) , Tkinter (tk) , pathlib  , keras , layers , Sequential , filedialog
## Result
Architecture	Accuracy
1.	CNN	99%
2.	ResNet50	96%
3.	Vgg16	49%
4.	InceptionV3	97%

## Abstract 
As we have been seeing the exponential growth in the spread of covid-19, one of the major causes was the direct contact with the infected ones. For example, a family living in the same building has meals together and does their things altogether. And also a huge mass of people visiting the shopping malls and other public places. It was set necessary for everyone to put on the face masks while being entered in public places. It is quite impossible to check each and every person on the entrance if they have their face masks put on or not. So, there was a need to build such a system that could automatically detect the people with or without the face masks.
### step 
We gathered the dataset. 5000 images labeled ‘With Mask’ and 5000 images labeled as ‘Without Mask’. The next step was to choose the tool so we used Jupiter Notebook to work. We used CNN, ResNet50, Vgg16, and InceptionV3 to handle this problem. Following are the steps carried out.
1.	Import all the libraries (all libraries are given below )
2.	Upload the data
3.	Preprocess the data
•	Set the size of the input images (10,000 images)
•	Split the dataset i.e. 80% training (8,000 images) and 20% testing (2,000 images)
4.	Train the model {model are cnn,vgg16,resnet50,inceotion}
5.	Run the model
6.	Plot the accuracies and losses
7.	Take the image from the directory to test
8.	Make a prediction for the image



## Conclusion 
Different results were archived after the processing of the proposed four architectures. Out of which, CNN showed the best results with an accuracy of 99%. Hence for this specific problem, we can apply  CNN to apply for the ‘Face Mask Detection’. In the future, we want to extend our work by expanding this dataset into three classes labeled: ‘With Mask’, ‘Without Mask’ and ‘Improper Mask’, and also we will be applying the latest Machine Learning approaches at that time
