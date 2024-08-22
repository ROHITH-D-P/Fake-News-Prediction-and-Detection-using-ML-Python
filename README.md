  FAKE NEWS PREDICTION AND DETECTION

🔹I'm happy to share my 1st project " Fake News Prediction and Detection " on Virtual Data Science Intern using Machine Learning Algorithms.

🔹Fake news has become a pervasive problem in the digital age, posing significant challenges to the credibility of information disseminated through various media channels. The proliferation of false information can lead to widespread misinformation, influence public opinion, and cause socio-political and economic disturbances. This project aims to develop a machine learning-based system for detecting fake news, leveraging Machine Learning techniques to analyze and classify news articles as either genuine or fake.

🔹The dataset utilized for this project comprises news articles labeled as fake or true. The project workflow includes data preprocessing, feature extraction, model training, and evaluation. Preprocessing steps involve cleaning the text data, removing stop words, and normalizing the text. Feature extraction is performed using methods such as TF-IDF (Term Frequency-Inverse Document Frequency) to convert textual data into numerical representations suitable for machine learning algorithms.

🔹Multiple classification algorithms, including Logistic Regression, Decision Tree Classifier and Random Forest Classifier are employed to train models on the dataset. The performance of these models is evaluated using metrics such as accuracy, precision, recall, and F1-score. Cross-validation techniques are employed to ensure the robustness and generalizability of the models.

![image](https://github.com/user-attachments/assets/36a39db3-8f0b-4bda-8c7d-24211d14250b)

Load the Dataset
(i) Loading the Fake News Dataset
![image](https://github.com/user-attachments/assets/f641109b-6815-4b8b-ad0a-a6adc9f5af99)

(ii) Loading the True News Dataset
![image](https://github.com/user-attachments/assets/97ae8b51-be02-4d44-95c2-e27a7e22e01a)

DATA PREPROCESSING
(i) Displaying first 10 rows of the Fake News
![image](https://github.com/user-attachments/assets/8887b0a9-8a19-4a6a-83bf-c8054d813ef9)

(ii) Displaying first 10 rows of the True News
![image](https://github.com/user-attachments/assets/37fa2fc4-5891-452e-8ae0-78abb6c4b6ba)

Adding a column as '0' for Fake and '1' for True News
![image](https://github.com/user-attachments/assets/ab60ed2c-9a62-49a7-9046-8ae5bc3d70f2)

Size of the fake and true news tables
![image](https://github.com/user-attachments/assets/39f8f801-4980-4723-9a3a-03dea367a99a)

Removing empty rows
![image](https://github.com/user-attachments/assets/247d4b7e-7387-4ffd-a173-85b4227e66bc)

Checking the size of the both tables after handled the empty rows
![image](https://github.com/user-attachments/assets/d2f1edda-e8e4-400f-ab48-6d35fe6a1bea)

Displaying last 10 rows for the Fake News table
![image](https://github.com/user-attachments/assets/937d224c-c166-4e3b-9bf0-147e20d59854)

Displaying last 10 rows for the True News table
![image](https://github.com/user-attachments/assets/a1a5217c-e772-415e-9d67-b638432cb708)

Merging Both the Fake News and True News tables to a single table
![image](https://github.com/user-attachments/assets/7db8b432-deda-4e32-97a4-8a713f5d28ff)

Displaying the first 10 rows of the merged table
![image](https://github.com/user-attachments/assets/1b1ab4c0-51ac-4f8d-b9a4-d437b6ab0399)

Displaying the last 10 rows of the merged table
![image](https://github.com/user-attachments/assets/71f8ef02-4992-4d4e-85f1-17b1dd4636f6)

Checking the size of merged table
![image](https://github.com/user-attachments/assets/ea89ea9b-ca13-42dd-b971-43e2fe81563e)

Identifying the column names
![image](https://github.com/user-attachments/assets/569f7dbd-5761-4f0b-9ff3-45f1566927db)

Dropping the columns which are not required for the further process
![image](https://github.com/user-attachments/assets/8ce6a8b9-9815-4fc7-9b1e-5f2f6439e506)

Checking null values if they exists but its not necessary becasuse we already removed the empty rows
![image](https://github.com/user-attachments/assets/a6b87c7e-97ea-4648-9abb-f3bacd1f1fdd)

Displaying the column names after removed the unwanted columns
![image](https://github.com/user-attachments/assets/860e3551-2fac-4341-be1e-348c00cb2de5)

Shuffle the data set and later we can see the data which are shuffled 
![image](https://github.com/user-attachments/assets/1a3c1176-71e0-4edd-88f7-e2039e51d31b)

Importing Regular Expression -> re library
![image](https://github.com/user-attachments/assets/c3bbef81-60d1-4d13-8e23-3d420d2636f4)

Train, Test and Split the data
![image](https://github.com/user-attachments/assets/afc77c41-abb5-47d2-820a-04ebad148ff3)

TFID VECTORIZATION
![image](https://github.com/user-attachments/assets/55cae0ce-a3cd-45f8-b3e7-d5abfb915586)

LOGISTIC REGRESSION
![image](https://github.com/user-attachments/assets/0948122f-cff6-4529-94dd-75bde1fab761)
![image](https://github.com/user-attachments/assets/be0039b8-5446-49a8-b76c-e3b2a5e0b5c6)

DECISION TREE CLASSIFIER
![image](https://github.com/user-attachments/assets/c4dcfaf2-eaf9-40f3-8e57-288da1f4b566)

RANDOM FOREST CLASSIFIER
![image](https://github.com/user-attachments/assets/101d4d10-a3dd-4462-bcbe-9fc50f6f6a7b)

Defining Manual testing 
![image](https://github.com/user-attachments/assets/8b87ae78-25cd-42a0-8219-dcbecda05cff)

Now the news is detected whether fake or true
![image](https://github.com/user-attachments/assets/0c12aacb-b4bd-42d7-b7b3-289d3dd38267)
![image](https://github.com/user-attachments/assets/e4983813-a708-47ce-9598-115c4e9603bc)

🔹The results demonstrate the efficacy of the proposed system in accurately distinguishing between fake and true news articles. The model's predictive performance highlights its potential application in real-world scenarios, such as social media platforms and news aggregators, to combat the spread of misinformation.

🔹In conclusion, this project presents a comprehensive approach to fake news detection using machine learning and NLP. The developed system contributes to the ongoing efforts to uphold information integrity and offers a viable solution to mitigate the adverse effects of fake news on society. Future work will explore advanced deep learning techniques and the integration of additional contextual information to further enhance the accuracy and reliability of the detection system.

🔹I would like to thank Hellotech Softwares for the guidance.
  
Follow me on LinkedIn :- [https://www.linkedin.com/in/rohith-d-p](url)

#FakeNewsDetection #DataScience #MachineLearning #Intern #HelloTechSoftwares #Project
