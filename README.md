# Human-Age-Ethnicity-Detection
![image](https://www.internationalairportreview.com//wp-content/uploads/facial-recognition-3.jpg)

# Business Understanding
Image classification is one of the algorithms used in deep learning for machine learning. In this project, I will be detecting human age from face images. I have downloaded the dataset from https://susanqq.github.io/UTKFace/. The website has about 24,000 images of human faces that are ages 0-116. Detecting ages from face images can/is used in several cases, such as screening minors so that there won’t be any underage people buying alcohol/tobacco/etc., (will add more later). I have binned the ages in 5 categories: 0-20, 21-26, 27-40,  21-35, 36-50, 51+. I binned the ages in this way to make sure that I have balanced classes.

# Ethical Issue on Face Recognition
Face Recognition has been one of the popular software using deep learning. However, face recognition is one of the most controversial machine learning algorithms. I am going to talk a little about the ethical issues to show that this project will not be used for any such problematic reason.

One of the major ethical issues is that many of these images are used without consent. This causes many problems since people do not like their faces used without their knowledge. Even when asked for consent, many people feel uncomfortable using their photos for research. The website I have downloaded this from have stated that they did not get consent. Thus, I will not be using the images other than just this project. 

Another major ethical issue is using ethnicity in face recognition modeling. Many have wrongly used deep learning to discriminate against certain races. In this project, I have not used ethnicity as one of the feature predictions and just focused solely on age.
I have used https://www.nature.com/articles/d41586-020-03187-3 as a resource. There are many other articles stating ethical issues on face recognition deep learning. Please search for more if interested.

# Data Process
From the website https://susanqq.github.io/UTKFace/, I downloaded the three zip folders named part1, part2, and part3. After unzipping the folders in a folder called ‘Human_Face_Regonition_Images’, I created another folder called images to combine all the images into one folder. From the images folder, I created another folder called split to randomly split the images into three different folders: train, validation, test. Now, we have processed our data for modeling.

![output5](https://user-images.githubusercontent.com/87672665/137989104-a2f31c28-a0d1-4a04-a967-72bc5232d937.png)

The distribution of the ages are not normally distributed. From the graph above, you can see that the data has more images that are ages 1 and 26.

![output7](https://user-images.githubusercontent.com/87672665/137989054-04ed89a4-19af-41a0-9f9c-4ff5eac4f5fe.png)

Since the distributions are not proportional, I binned the ages into 5 classes to make the number of images be similar between each class.

# Result
(placeholder)

# Deployment
(picture place holder)
I created a Flask app to deploy my model. To deploy this webpage, you need to make sure your Flask environment is activated. Then, in your terminal, run python app.py (make sure you are in the project directory).
In the app, you submit a human face image and the image will display with the predicted age.

# Structure
