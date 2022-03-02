# Bitcoin price prediction using LSTM based models.
<p align="center">
  <img src="images/02_Polimi_bandiera_BN_positivo_outline.jpg" style="width:600px;height:250px"/>
</p>
<p align="center">
  <img src="images/bitcoin_logo.jpeg" style="width:150px;height:150px"/>
</p>


#### Team Members:
* [Piero Rendina](https://github.com/PieroRendina)
* [Andrea Sanchini](https://github.com/AndreaSanchini)

## Dataset
The dataset is drawn from through the <a href="https://pypi.org/project/yfinance/" target="_blank">Yahoo API</a>

## Models
The project deals with the full implementation, training and testing of machine learning models to forecast the Bitcoin trends.  
The models are inspired by scientific papers and their training configuration is the result of endless trials and errors. 
They belong to two different classes known as 
* **sequence-to-vector** models: prediction of the Bitcoin closing price *one time-step ahead* after having inspected a window of **n** consecutive time-steps
* **sequence-to-sequence** models: prediction of the Bitcoin closing price trend over *one time-span ahead* after having inspected a window of **n** consecutive time-steps

## Contents
For a more detailed description of the development process, the training and the testing of the models, please refer to the notebook and to the report of the project.



