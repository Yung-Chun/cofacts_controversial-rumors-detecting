# cofacts_controversial-rumors-detecting

## 01_owd_statistics_clean
correct data from Our World Data 

## 02_cofacts_split&clean_data
import word segment file
data cleansing: transform simplified chinese to traditional chinese, delete English characters and digits, define categories and filter. 

## 03_cofacts_define_rumor
define whether this report is rumor by calculating its fact-check replies and netizens' reactions. 

## 04_cofacts_clustering
cluster reports via HAC+KNN  
Reference: https://medinform.jmir.org/2021/11/e30467  

## 05_cofacts_tedency_stats
calculate Pearson's correlation coefficient, cosine similarity, and kurtosis  
sort data  

## 06_cofacts_vis_overview
overview visualization  

## 07_cofacts_vis_tendency
tendency visualization  
