# Traffic-Sign-Classification  
Built a model using Convolutional Neural Network to train the machine to identify different Traffic Signs. 
First attempt on using deep learning models.  

Dataset used: German traffic signs.  
https://bitbucket.org/jadslim/german-traffic-signs   
The training dataset consists of over 30,000+ traffic sign images which are used to train the model.  
The validation dataset consists of about 4500 images to test and validate the model after training it.  
And the test dataset consists of about 12,000 images on which model is applied to predict the traffic sign.

Tool used: Google Colab  
Colab is a free Jupyter notebook environment that runs entirely in the cloud. Most importantly, it does not require a setup and offers free Cloud service with free GPU. Colab supports many popular machine learning libraries which can be easily loaded in the notebook.  

Model: CNN neural network  
CNN is prefered here because the dataset consists of images and CNN model works better on images as compared to other neural network models.  
Keras is the primary python library used for making CNN models. With its various packages, Keras simplifies the job of creating model when compared to TensorFlow, which was used before Keras was introduced.  
CV2 from OpenCV is the another library used for the image manipulation and processing.  

Result: After running 50 epochs on the model, the results were found to be-  
Test Accuracy: 91.28%  
Training Accuracy: 94.95%  
Validation Accuracy: 93.31%  
