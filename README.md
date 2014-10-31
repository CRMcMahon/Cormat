Cormat
======

Correlation Matrix Tool for Air Monitoring Network Assessment

datacleanup.R 
  This script formats the source air pollution concentration and air monitoring site information for use in the cormat tool
    - air pollution source data is an AQS AMP 435 Report (Daily Summary Report)
        parameter codes: 88101,88502,44201
        duration codes: 7,X,W
    -Air monitoring site source data is an AQS AMP 500 Report
        parameter codes: 88101,88502,44201
        region codes: 01,02,03,04,05,06,07,08,09,10
  
cormat_server_test_2.R
  This script call the formatted data sets and calculates and plots the correlation matrix results 
  

