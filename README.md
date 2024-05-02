<h1>Rock vs Mine Prediction using SONAR Data</h1>
<h2>About</h2>
Outwardly SONAR technique has exploited the discovery of rocks and minerals which would have been very difficult otherwise. The technique exploits certain parameters which will aid to detect the surface targets or obstacle such as a rock or a mine. Machine learning has drawn the attention of maximum part of today’s emerging technology, related from banking to many consumer and product based industries, by showing the advancements in the predictive analytics. This prediction can be done using machine learning algorithm such as logistic regression which is implemented in google colab.
<br><a href="https://colab.research.google.com/drive/1gtqf2LBAbhQLxUPvbM4nSUYhmKZ27--k?usp=sharing" >Google Collab </a><br>
<h2>DataSet</h2>
The dataset has been collected from UCI Repository. It has come across 61 features which define and differentiate Rocks and Mines and comprises of 208 samples. This data is used for training and testing purpose. The Last column in this dataset indicates that, whether it's a mine or a rock, which is useful in prediction. The dataset is included in this repository.
Filmpire combines the desire to unleash powerful creativity with the industry's most advanced JavaScript tools including React.js, Redux, Material UI, Alan AI, and more.
<h2>Model</h2>
The model used here is Logistic Regression. Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable. Logistic Regression uses a sigmoid or logit function which will squash the best fit straight line that will map any values including the exceeding values from 0 to 1 range. So it forms an “S” shaped curve. Sigmoid func. removes the effect of outlier and makes the output between 0 to 1. As it a binary classification model it is perfect to predict if an object is mine or rock based on the sonar data.
<h2>Description</h2>
Sonar data in a csv file is taken for training and testing purpose. Data preprocessing is done on the available sonar data which is suitable for training the model. After Data preprocessing, a Logistic regression model is built. The dataset is split into testing and training sets. The training data is used to train the model then the new data/ testing data is given to the trained logistic regression model for prediction.
<h2>Lessons Learned</h2>
<ul>
  <li>This is my first machine learning project where i learnt about logistic regression model which is used for binary classification.</li>
  <li>I also learned about how different python libraries like scikit learn, numpy and pandas can be used to build and train the model.</li>
  <li>Model evaluation using input data was also done in this project.</li>
</ul>
