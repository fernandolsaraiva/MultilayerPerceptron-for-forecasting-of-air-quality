# mlp_regression_air_quality

# Task 
Considerar:

* Diferentes topologias (>=5 topologias, variar número de
camadas

* Usar o algoritmo original SGD (não usar algoritmos otimizados,
e.g. ADAM)
* Avaliar o impacto do uso do Momentum
* Avaliar o impacto do uso da regularização (i.e. L2)
* Ilustrar graficamente a evolução do treinamento (treino/validação).

# Introduction

In  this project, we have used a data set with measurements of an Air Quality Chemical Multisensor Device to predict the CO level in the air 1 hour in advance.

Description of the dataset (from https://archive.ics.uci.edu/ml/datasets/air+quality)

* 0 Date (DD/MM/YYYY)
* 1 Time (HH.MM.SS)
* 2 True hourly averaged concentration CO in mg/m^3 (reference analyzer)
* 3 PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)
* 4 True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer)
* 5 True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)
* 6 PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)
* 7 True hourly averaged NOx concentration in ppb (reference analyzer)
* 8 PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
* 9 True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)
* 10 PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
* 11 PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)
* 12 Temperature in Â°C
* 13 Relative Humidity (%)
* 14 AH Absolute Humidity

In this work, we evaluate the application of different architectures of Multilayer Perceptron (MLP) Neural Networks to perform a regression task.
