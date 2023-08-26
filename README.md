## FaceMaskDetection
A Machine Learning project for the prediction of FaceMask. The dataset used is " Face Mask " where the train data has 1000 images and the test data has 992 images. I have indexed the images with have mask as '0' and without mask as '1'. I have done reshape for all the elements with the target_size=(64,64). 
These are the steps followed while doing this project listed below. 

Step 1: Import the libraries required.

Step 2: Data Preprocessing
    
    Step 2.1: Preprocessing the training data.
    
    Step 2.2: Preprocessing the testing data.

Step 3: Building the CNN model
    
    Step 3.1: Initialising the CNN.
    
    Step 3.2: Add the two layer having Convolution, Maxpooling, Dropout layers.
    
    Step 3.3: Convert into 1D vector using Flatten().
    
    Step 3.4: Make it full connection and add output layer. Since it is the binary class classification we use the activation layer as sigmoid in the output layer.
    
    Step 3.5: Compile the CNN model.
    
    Step 3.6: Training the CNN on the training set and evaluating it on the test set.

Step 4: Making the single prediction

Download the dataset from the below link:
[https://www.kaggle.com/datasets/sanknn/face-mask-detectionhttps://www.kaggle.com/datasets/sanknn/face-mask-detection]()
    
