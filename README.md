# Machine-Learning-Project
# "Automated extraction of handwritten text from images"

Handwriting recognition (HWR), also known as Handwritten Text Recognition (HTR), is the ability of a computer to receive and interpret intelligible handwritten input from sources such as paper documents, photographs, touch-screens and other devices. This project seeks to classify an individual handwritten word so that handwritten text can be translated to a digital form. The main approach used to accomplish this task i.e, classifying words directly is Convolutional Neural Network (CNN) with various architectures to train a model that can accurately classify words.
<br>

<img src="https://user-images.githubusercontent.com/60837428/107010519-733fb680-67bc-11eb-815e-d8053f6fd608.png" width="90%"></img> 
<br>

Handwritten text is a very general term, and we wanted to narrow down the scope of the project by specifying the meaning of handwritten text for our purposes. In this project, we took on the challenge of classifying the image of any handwritten word, which might be of the form of cursive or block writing.

<img src="https://user-images.githubusercontent.com/60837428/107010530-776bd400-67bc-11eb-896c-cf542c2ae09f.png" width="90%"></img> 
<br>

# Description of Project
The objective of this project is to identify handwritten characters with the use of neural networks. We have to construct suitable neural network and train it properly. The program should be able to extract the characters one by one and map the target output for training purpose. After automatic processing of the image, the training dataset has to be used to train “classification engine” for recognition purpose. The program code has to be written in Python and TensorFlow and the dataset used is the IAM handwritten dataset.

To solve the defined handwritten character recognition problem of classification we used Google colab computation software. The computation code is divided into the next categories:
1. Collect handwritten images.
2. Split the data into the train set(80%) and the test set(20%) for further use.
3. Use Dimension reduction techniques.
4. Train classification model on the training dataset using neural network.
5. Validate the model on the test data.
6. Fine tune the parameters for increase in classification that accurates the model on train and test data.

After training the model the accuracy comes out to be 0.2522335946559906

The images generated in predicting the accuracy of the model are:
<br>
<img src="https://user-images.githubusercontent.com/60837428/107011067-27d9d800-67bd-11eb-9539-9f821d2f4959.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011099-33c59a00-67bd-11eb-8736-99518a0eaecf.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011111-39bb7b00-67bd-11eb-8a5e-8b72d2c1c8c3.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011125-3e802f00-67bd-11eb-8413-58ac66bd07a8.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011137-4344e300-67bd-11eb-874f-ff9de69b1328.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011149-47710080-67bd-11eb-958a-fb4beaec2bb2.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011163-4b048780-67bd-11eb-8267-ccf4ebd87675.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011172-4f30a500-67bd-11eb-94bc-9ec41e3c0236.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011179-52c42c00-67bd-11eb-9b1a-b853b473ebdd.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011192-5657b300-67bd-11eb-8a8f-9c9d2aa97be3.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011207-5a83d080-67bd-11eb-8525-dba9e2d8b722.png" width="23%"></img> <img src="https://user-images.githubusercontent.com/60837428/107011216-5e175780-67bd-11eb-912d-e48181b4861a.png" width="23%"></img> 











 

