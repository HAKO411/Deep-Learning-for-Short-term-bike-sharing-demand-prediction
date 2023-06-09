# Deep Learning for Short-term bike-sharing demand prediction: LSTM and CNN-LSTM

Submitted by:
Tri Dung Huynh, Email: tri.huynh@st.ovgu.de
&
Md Asaduzzaman, Email: md.asaduzzaman@st.ovgu.de

Supervisor:
Jun.-Prof. Dr. Kai Heinrich

## Abstract

The bike imbalance issue may lead to decreased service reliability, user discontent, and decreased attraction and user commitment in the bike-sharing program, failing to achieve sustainable transportation system implementation expectations.”- which may require accurate forecasting of convenient demand. These studies have shown how weather conditions can affect how many bikes are demanded at bike-sharing stations at times of the day and weeks. It will be easier for operating agencies to rebalance bike-sharing systems in a timely and efficient manner if we can predict the short-term demand for bike-sharing. We use Helsinki city historical trip data from 2016 to 2020, along with extra inputs such as weather conditions, demand-related engineered features, and temporal variables related to demand. As opposed to statistical methods, deep learning methods can automatically learn the relationship between inputs and outputs, requiring fewer assumptions and achieving higher accuracy. Since their spatiotemporal functional observations are similar, the CNN and LSTM need to be segmented into time frames like hourly, daily, weekly, and monthly, in order to model the Helsinki bike-sharing station data effectively. We provide quantitative results show that accurate short-term demand (CNN-LSTM_336) was noticeable between the Models.

## Key Words: 
*Bike sharing system; deep learning model; ARIMA model; Convolutional Neural Network (CNN); Long Short-Term Memory Network (LSTM)*


## Research paper:
Our full research paper [here](https://github.com/HAKO411/Deep-Learning-for-Short-term-bike-sharing-demand-prediction/blob/main/Submission%20Paper.pdf)  
Our presentation for the research [here](https://github.com/HAKO411/Deep-Learning-for-Short-term-bike-sharing-demand-prediction/blob/main/Presentation.pdf)

### Data Preprocessing

<img width="1276" alt="Screenshot 2023-06-08 at 8 53 39 PM" src="https://github.com/HAKO411/Deep-Learning-for-Short-term-bike-sharing-demand-prediction/assets/61934483/f4b615e1-7b5a-48b9-8112-5d202c7a9437">

### Data Structure Design

<img width="1290" alt="Screenshot 2023-06-08 at 8 54 55 PM" src="https://github.com/HAKO411/Deep-Learning-for-Short-term-bike-sharing-demand-prediction/assets/61934483/95be37d5-8d31-4344-a54f-01c488d07f06">

### The layered structure of LSTM and CNN-LSTM models
![Layers](https://github.com/HAKO411/Deep-Learning-for-Short-term-bike-sharing-demand-prediction/assets/61934483/26eb08a5-b350-4266-bfe0-e693aafaa43e)

### Time Lags with LSTM and CNN-LSTM in Prediction Accuracy
<img width="1282" alt="Screenshot 2023-06-08 at 8 56 41 PM" src="https://github.com/HAKO411/Deep-Learning-for-Short-term-bike-sharing-demand-prediction/assets/61934483/0e7a97ed-9c2a-4803-ae8f-75b577ba7e86">

### Average Pickups Demand in Prediction Accuracy
<img width="1261" alt="Screenshot 2023-06-08 at 8 57 49 PM" src="https://github.com/HAKO411/Deep-Learning-for-Short-term-bike-sharing-demand-prediction/assets/61934483/495287a0-75d7-409a-b9b9-ae2ca1da1aa7">




