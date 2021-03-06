# Battery Charge-Discharge Schedule

In this project, an algorithm is developed to charge and discharge a battery being given PV-generation and Demand Load forecasts. 
The present algorith was developed for the [WPD - Catapult Energy Systems](https://es.catapult.org.uk/) Challenge with the [data](https://www.westernpower.co.uk/innovation/pod/dataset/) in that time provided, now public. 

The main goal of the challenge was to optimize the use of pv resource and at the same time, reduce as much as possible the afternoons demand load peak.

The output of the presented algorithm is a time serie with the charge-discharge rate of the battery. Try it out in Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ERafaelMartinez/Battery_Charge-Discharge_Schedule/blob/main/ChargingUltimate.ipynb)

The constraints ont he battery system and a further description of the challenge you can find it on the pdf document included in this repository. The forecasting of the demand and pv generation time series is not included in this work. 
If you're interested on that one, feel free to check [energy_forecasting_LSTM_vs_FCNN](https://github.com/ERafaelMartinez/energy_forecasting_LSTM_vs_FCNN) out.

