# Image-Classification-using-CNN
MAJOR PROJECT DOCUMENTATION
Image Classification using CNN
-Pawan Surya

Overview : 
This project is an image classifier using Convolutional Neural Networks . The dataset used is the CIFAR-10 dataset . The deployment is done by the Streamlit environment .
Stepwise brief : 
1.	Dataset collection : The dataset is the CIFAR-10 dataset which consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
2.	Data Preprocessing : The CIFAR - 10 dataset  is already preprocessed and split into train and test data .  Images are normalised to a range of [0, 1] and labels are converted to categorical format.
3.	CNN Model Architecture : The architecture combines several convolutional layers, pooling layers, dropout layers, batch normalisation, and dense layers. It follows a sequential design (Sequential model in Keras), where layers are stacked sequentially. While it's not a specific well-known architecture like VGGNet or ResNet, it incorporates common elements seen in deep CNNs designed for image classification tasks.
4.	Model Training : The model is trained using the training data with a learning rate of 0.0001 , batch size 32 and uses the adam optimiser 
5.	Model Evaluation :  The  trained model is evaluated using the testing dataset by calculating  metrics such as accuracy,precision, recall, and F1-score to assess the model's performance.
6.	Model Optimisation : The model is fine tuned by augmenting the training data and adding more layers to the model .
7.	Deployment and Interface : I used the streamlit environment for the front end and ngrok for a public url . 

