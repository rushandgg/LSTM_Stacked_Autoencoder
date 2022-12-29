# LSTM Stacked Autoencoder

**- Data Set :** Samsung Electronics Stock Price(Close), 2016-01-04 ~ 2021-12-30<br/>
**- Tool :** Python, Jupyter Notebook, Tensorflow, Keras<br/>
**- Model :** LSTM Stacked Autoencoder<br/>
**- Purpose :** Denoise stock price<br/>
**- Reference :** Stacked LSTM Sequence-to-Sequence Autoencoder with Feature Selection <br/>
      for Daily Solar Radiation Prediction: A Review and New Modeling Results
<br/>
<br/>
**- My Plan :** (1) Output inverse_transform and estimate MSE <br/>
     (2) Make a trading strategy with this graph <br/>
     (3) Develop trading program with securities's API <br/>
     (4) Kiwoom Securities https://www.kiwoom.com/h/main <br/>
      
# 1. Model Shapes

![model_shapes](https://user-images.githubusercontent.com/60992415/186334667-97bf0ec6-fb1f-44bd-b673-04559de97685.png)

# 2. Loss Graph

![Loss](https://user-images.githubusercontent.com/60992415/186334998-e45ba62f-dbcd-4a20-b6d8-aa6204414009.png)

# 3. Output Graph

![output](https://user-images.githubusercontent.com/60992415/186335089-c19e08d6-464e-45b0-b76d-640ebd4dca67.png)
