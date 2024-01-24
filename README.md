# regression-analysis-turbine-energy-yield

Data Set Information:

The dataset contains 36733 instances of 11 sensor measures aggregated over one hour (by means of average or sum) from a gas turbine located in Turkey's north western region for the purpose of studying flue gas emissions, namely CO and NOx (NO + NO2). The data comes from the same power plant as the dataset <http://archive.ics.uci.edu/ml/datasets/Gas+Turbine+CO+and+NOx+Emission+Data+Set.com> used for predicting hourly net energy yield. By contrast, this data is collected in another data range (01.01.2011 - 31.12.2015), includes gas turbine parameters (such as Turbine Inlet Temperature and Compressor Discharge pressure) in addition to the ambient variables. Note that the dates are not given in the instances but the data are sorted in chronological order. 

Attribute Information:

The explanations of sensor measurements and their brief statistics are given below.

-Variable (Abbr.) Unit Min Max Mean

-Ambient temperature (AT) C â€“6.23 37.10 17.71

-Ambient pressure (AP) mbar 985.85 1036.56 1013.07

-Ambient humidity (AH) (%) 24.08 100.20 77.87

-Air filter difference pressure (AFDP) mbar 2.09 7.61 3.93

-Gas turbine exhaust pressure (GTEP) mbar 17.70 40.72 25.56

-Turbine inlet temperature (TIT) C 1000.85 1100.89 1081.43

-Turbine after temperature (TAT) C 511.04 550.61 546.16

-Compressor discharge pressure (CDP) mbar 9.85 15.16 12.06

-Turbine energy yield (TEY) MWH 100.02 179.50 133.51

-Carbon monoxide (CO) mg/m3 0.00 44.10 2.37

-Nitrogen oxides (NOx) mg/m3 25.90 119.91 65.29

Purpose of this Project:
We try to predict TEY (Turbine energy yield ) with the help of some gas ratio and pressure, temperature , humudity in atmosphere and turbine inner features. For the best prediction of the powerplant's TEY(TURBİNE ENERGY YIELD):

- Preparation of data like eliminating outlier, dealing with missing values for plotting ,testing, modelling

- Understanding data statistical features like mean, standart deviation,etc..

- Plotting variables features and their relations, 

- Applying hypothesis test to make inferences on the aspects of probability of admission chances.

- Check assumptions for llinear regression and if necesarry making transformation of variables

- Conduct linear regression, evaluate results of model

- Improving  linear regression to find better result

- if it is not suitable try to other regression models and making evaluation and improving processes again for each model.

- Deciding Final model and making a conclusion
