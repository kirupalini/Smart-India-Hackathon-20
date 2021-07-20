# Smart-India-Hackathon-20
The problem statement is ***Detection of child predators/ cyber harassers on social media*** posed by the Bureau of Police Research and Development.

The system consists of 2 major functionalities:

* Age Detection for filtering out minors(using DNN) 
* Predicting for grooming or non grooming charecteristics in the conversations between minors and adults(using svm classifier).

1.fchatroom.py: This module has the chatroom code and performs all the Backend operations including the DB commands.

2.login.html: The html page for login into chatroom.

3.session.html: Front end code for chatroom.

4.age1.py: The module for age detection using DNN.

5.dnn1.py: DNN training.

6.svm.py: Has the svm classifier code for detecting if the conversation is grooming or not.

7.svmtest.py: For testing the svm classifier.

8.bigdic.dic: The dictionary of english words, including slang words and their corresponding stages.

# Technologies Used
 ![](https://img.shields.io/badge/Language-Python-informational?style=flat&logo=data:image/svg%2bxml;base64,<BASE64_DATA>) <br>
* Keras, Sklearn
* Pandas, NLTK, liwc
* Flask
* MySQL
* HTML, CSS, Javascript
