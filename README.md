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


The Part 1 folder contains a python notebook where the Artificial Neural Network model is implemented for the first question.
It also contains the excel file with the infected probability values.

The Part 2 folder contains 2 python notebooks where the LSTM model is implemented along with the Neural Network model
