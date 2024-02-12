# Transfer-Learning-Model-for-Glaucoma-dataset

Xception
A Convolutional Neural Network model for my internship which is a solution to binary classification problem. Biomedical images are very hard to build models on. Even with the best models, it's hard to achieve very high accuracies. I tried to overcome this problem throughout my internship.

Worked on Glaucoma dataset from Kaggle which can be found [here.](https://www.kaggle.com/datasets/deathtrooper/eyepacs-airogs-light/code)
If you want to work on the model, you should follow the link. Code won't work on any enviorment except Kaggle notebook, since I imported the data from there. The code is also available at the dataset's page. (Xception 93.5%)

![EyePACS-NRG-2772](https://github.com/KeremK64/Transfer-Learning-Model-for-Glaucoma-dataset/assets/105675626/f928874f-d578-4907-a6b5-39b8f1ddda11)


Used transfer learning techniques to create the model. Pre-trained model I used is Xception which is available on keras.applications library. Also used some data augmentation techniques to achieve high accuracy. 

Achieved ~93.5% accuracy on this model, which is the highest among my models.  
![image](https://github.com/KeremK64/Transfer-Learning-Model-for-Glaucoma-dataset/assets/105675626/4ab7b778-84bd-45e1-aa6c-d9cebc821d90)


Also you can find another models in the repo. In Neural-network file you can find a model that is more traditional and basic. This model was one of the first models I created at the start of my internship. It achieved lower accuracy as expected. InceptionResnet is another model which can be found on keras.applications library. I used data augmentation to achieve better results all on my models. 

Concatenate and average files contains models that is created by ensemble learning techniques. In concatenation technique, we are simply concatenating models to reach an output. In average technique, we are using majority voting. Each model comes with an output and the most voted output remains as actual output. Unfortunately neither of these techniques achieved better accuracy. So I reached 93,5% as my best accuracy throughout my internship with Xception. 

Also an article will be published about these models(there are 50 of them). 
