# Transfer-Learning-Model-for-Glaucoma-dataset

A Convolutional Neural Network model for my internship which is a solution to binary classification problem. Biomedical images are very hard to build models on. Even with the best models, it's hard to achieve very high accuracies. I tried to overcome this problem throughout my internship.

Worked on Glaucoma dataset from Kaggle which can be found [here.](https://www.kaggle.com/datasets/deathtrooper/eyepacs-airogs-light/code)
If you want to work on the model, you should follow the link. Code won't work on any enviorment except Kaggle notebook, since I imported the data from there. The code is also available at the dataset's page. (Xception 93.5%)

![EyePACS-NRG-2772](https://github.com/KeremK64/Transfer-Learning-Model-for-Glaucoma-dataset/assets/105675626/f928874f-d578-4907-a6b5-39b8f1ddda11)


Used transfer learning techniques to create the model. Pre-trained model I used is Xception which is available on keras.applications library. Also used some data augmentation techniques to achieve high accuracy. 

Achieved ~93.5% accuracy on this model, which is the highest among my models.  
![image](https://github.com/KeremK64/Transfer-Learning-Model-for-Glaucoma-dataset/assets/105675626/4ab7b778-84bd-45e1-aa6c-d9cebc821d90)


You can also follow the leaderboard for this dataset from [here](https://github.com/TheBeastCoding/glaucoma-dataset-metadata/blob/main/benchmark-eyepacs-airogs-light.md).
