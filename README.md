# LSTM-for-recommendation-system
The main motivation of this project is to improve the model of (Collaborative Filtering Recommender System) CFRS on Amazon reviews dataset performed with the (Long-short term Memory Sentiment Analysis) LSTM-SA. 
The result of the SA can be visualized to perform opinion mining of customers on a particular product and try to build better business strategies. 

For this project, the exploratory Data Analysis was carried out on the amazon cell phone and accessories dataset and sentence-level sentiment classification was performed on each and every review using LSTM-SA. 

- This is an overview of my proposed method for the LSTM-SA



![image](https://user-images.githubusercontent.com/82525775/157233327-f0419e24-8fbe-491f-8bc7-d5fa759a63fb.png)


As process, I used a pretrained global vector (GloVe) and the LSTM model to predict the new score toward the reviews. After getting the results in the first step, I integrate this in the RS based on the user-item collaborative filtering (CF) and evaluate the model based on the RMSE

