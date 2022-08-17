# Project Name
> We will build a multiclass classification model using a custom convolutional neural network in tensorflow to detect a skin cancer - melanoma.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- General information:To build a CNN based model which can accurately detect melanoma. 
- Background of  project : Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- Business probem  trying to solve  : A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Dataset that is being used : he dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

    Actinic keratosis
    Basal cell carcinoma
    Dermatofibroma
    Melanoma
    Nevus
    Pigmented benign keratosis
    Seborrheic keratosis
    Squamous cell carcinoma
    Vascular lesion

NOTE: We have not  used any pre-trained model using Transfer learning. All the model building process are based on a custom model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
		-  We used data The training accuracy seems to be nearly ~90%.
		- The validation accuracy is nearly ~80%.
        - We Rectified class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data: This has helped treat the overfitting to quite extent.
        - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
        - Choose an adam optimiser and categorical_crossentropy loss function for model training
        - Train the model for ~30 epochs

    

        
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- TensorFlow - version 2.9.1
- Python - version 3.10.0
- Keras - version 2.9.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Thanks to IITB and Upgrad team and coach for sharing the knowledge .
- References 
	- https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image_dataset_from_directory
	- https://www.tensorflow.org/tutorials/images/cnn
	- https://www.tensorflow.org/tutorials/images/data_augmentation
	- https://www.tensorflow.org/api_docs/python/tf/keras/layers/experimental/preprocessing/Rescaling
	- https://www.tensorflow.org/api_docs/python/tf/keras/layers/experimental/preprocessing/RandomFlip


## Contact
Created by [@chandan110791] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
