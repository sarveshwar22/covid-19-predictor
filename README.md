# Predicting the Growth and Trend of COVID-19 Pandemic

This study applies an improved mathematical model to analyse and predict the growth of the epidemic. An ML-based improved model has been applied to predict the potential threat of COVID-19 in countries worldwide. We show that using iterative weighting for fitting Generalized Inverse Weibull distribution, a better fit can be obtained to develop a prediction framework. This has been deployed on a cloud computing platform for more accurate and real-time prediction of the growth behavior of the epidemic. Interactive prediction graphs can be seen at: https://collaboration.coraltele.com/covid/.

## Quick installation of real-time prediction webapp

To install and run the dynamic real-time prediction webapp on your server run the following commands:
```
$ git clone https://github.com/shreshthtuli/covid-19-prediction.git
$ mv covid-19-prediction covid
$ chmod +x run.sh
$ ./run.sh
```
To access your server go to $HOSTNAME/covid/ from your browser. The webapp is hosted on https://collaboration.coraltele.com/covid2/ where graphs get updated daily based on new data.

## Dataset

We use the <i>[Our World in Data](https://github.com/owid/covid-19-data/tree/master/public/data/)</i> dataset for predicting number of new cases and deaths in various countries.

## Developer

[Sarveshwar Mahapatro](https://www.github.com/sarveshwar22)