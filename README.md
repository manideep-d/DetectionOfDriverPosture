# DetectionOfDriverPosture

**Abstract: -**
The distraction of drivers from the safe driving position is considered one of the major reasons for most road accidents. In this below project I am going to use some deep learning models to detect the position of a driver and classify the posture of a driver. The dataset is obtained from the kaggle which has 10 different classes of driver positions. The models used in this project are state of art algorithm VGG-16 and another CNN model. VGG-16 has obtained an accuracy of 96% and the CNN model has obtained an accuracy of 99%.


**Classes:-**
                {'c0': 'Safe driving', 
                'c1': 'Texting - right', 
                'c2': 'Talking on the phone - right', 
                'c3': 'Texting - left', 
                'c4': 'Talking on the phone - left', 
                'c5': 'Operating the radio', 
                'c6': 'Drinking', 
                'c7': 'Reaching behind', 
                'c8': 'Hair and makeup', 
                'c9': 'Talking to passenger'}


**VGG 16 Results:-**

<img width="489" alt="Screen Shot 2022-02-23 at 5 13 09 PM" src="https://user-images.githubusercontent.com/58058791/155418282-89111ca0-248f-4501-894a-32ec8e4b8aa0.png">

**Confusion Matrix of VGG16 Model:-**

<img width="587" alt="Screen Shot 2022-02-23 at 5 14 03 PM" src="https://user-images.githubusercontent.com/58058791/155418317-55864a43-24f1-4824-a9fa-bf097ec4ab2a.png">

**Modified CNN Test Results:-**

<img width="458" alt="Screen Shot 2022-02-23 at 5 17 50 PM" src="https://user-images.githubusercontent.com/58058791/155418777-33a86828-55ec-495f-8819-a3a78ace278f.png">


**Modified CNN Model Confusion Matrix:-**

<img width="587" alt="Screen Shot 2022-02-23 at 5 14 03 PM" src="https://user-images.githubusercontent.com/58058791/155418816-222a00a2-1a51-4aac-8676-d80ad65283f7.png">




**Conclusion:-**
From the above experiments, both vgg16 and cnn model has performed well with accuracy of 96 and 99 respectively. These models are able to predict the correct label from the unlabeled test images. From the future work perspective would like to perform the same experiments with more classification models like SVM, Naïve Bayes etc..


**For further details please read Driverposition.pdf**

