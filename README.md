# BANGKIT CAPSTONE PROJECT - PSYCARE
## MACHINE LEARNING PATH
### Machine Learning Member
      - Azzezza Nurul Fatima (M2004F0275)
      - Muhammad Apriliyandi (M7004F0271)
### Idea
Covid-19 Pandemic is one of the worst pandemic outbreaks in the last 100 years. This causes major problems in many sectors in every country and leads to a total lockdown. This has caused people to lose their jobs all over the world. Besides, there are risks for people to get sick from Covid-19 virus. This situation has led to many people having stress and mental health problems. 
Therefore, our team decided to make an application to help people determine their stress severity and give them suggestions to overcome their problems. ** This app will also be able to connect people to a psychologist so they’ll be able to share their burden and find a solution. **

### Dataset
We collected our [DataSet](https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses?resource=download&select=data.csv) Depression, Anxiety, and Stress responses fro Kaggle. We got 39775 response of Depression Anxiety Stress Scale (DASS). The response is based on 42 Questions and Extra informmation such as Country, Source, Major, Race, Orientation, etc.

### Machine Learning Flow Overview 
We use Visual Studio Code and some Python Library in this project, inclusing Tensorflow, numpy, Pandas, Matplotlib,Seaborn, IPhython.display, sklearn, Randomforest from sklearn, and Tensorflowjs. In this project before jumping into creating model, we cleansing data by finding out the presentation of NULL in each column. after removing unused data, we classify the Depression, Anxiety, and Stress data based on the Question that has categorized as the factor of each Condition. After that we scoring the Answer to findout the Total Score for each Depression, Anxiety, and Stress Questions this is for classifying the condition of each Depression, Anxiety, ans Stress whether its Normal, Moderate, or Severe. After that to make sure we just use the data that really is use and effect the condition we do the Feature Engineering by Feature scaling, Feature Importance, and Feature Selection. After that we Balancing the data so it wont overfiting for the model. To make sure the data is devide equally we devide the data with 80% Training & Test dataset and 20% Validation Dataset. As for the Model we use Neural Network. After making sure the model is appropriate by using Test dataset and also use validation dataset. we save the model for each Depression, Anxiety, and Stress into .h5 at first but then to JSON.
