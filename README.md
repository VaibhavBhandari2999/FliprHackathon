# FliprHackathon

This repo is made for the Flipr Hackathon Hiring Program 4.0
The track chosen by me was Machine Learning, and the question was related to COVID-19

This project is all about predicting the COVID-19 Infect_Prob in a person using the various different parameter avaliable in the dataset. The project is divided into 2 parts.

* Part-01: The objective of the first part of the problem statement is to predict the probability of a person getting infected by Covid-19 on 20th March 2020. The output file 01 should contain only people_ID and the respective infect_prob for the test data.

* Part-02: The Diuresis of a person is a time-dependent parameter, for which you have to come up with a Time-series prediction model. Using the Diuresis predicted by the model, you need to calculate the infect_prob on 27th March 2020 for every people_ID in the test data. . The output file 02 should contain only people_ID and the respective infect_prob on 27th March.


The dataset folder consists of a<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          1) Training dataset (with diuresis dataset)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          2) Testing dataset<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          3) Variable Descriptions<br>


For part 1, the model used is an Artificial Neurak Network(ANN). The ANN is trained on the Training Dataset and the best checkpoint is saved. The best checkpoint is then taken and the ANN is then applied on the Testing Dataset.<br> The predicted infected probabilties are then saved in an excel file.
The plot for the ANN predicted values are: <br><br>
![image](https://user-images.githubusercontent.com/30387574/77289149-64b0f380-6cff-11ea-87d4-4d47aaf9ebee.png)

The MSE and MAE error values for the ANN are:<br><br>
![Capture](https://user-images.githubusercontent.com/30387574/77289287-ad68ac80-6cff-11ea-9902-24179fd8b18f.JPG)

<br><br><br>
For part 2, the model used for the time series prediction is an LSTM model. The accuracy graph of the LSTM model is below: <br>
![Capture](https://user-images.githubusercontent.com/30387574/77289368-dab55a80-6cff-11ea-8e7d-6f9c2ab7b83e.JPG)
<br>
<br>The values got from the LSTM model are then replaced in the Training Dataset and the Neural Network is trained again.<br>
The plot for the ANN predicted values are: <br>
![image](https://user-images.githubusercontent.com/30387574/77289418-f6b8fc00-6cff-11ea-925f-8e44a22a51d2.png)

<br>The ANN is then applied on the Test dataset to get the predicted infected probability values, which are then saved in an excel file.
