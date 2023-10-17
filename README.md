# EY-Level-1-DS-Challenge

<p align="justify">EY Open Science Data Challenge 2023! The goal of Level 1 is to predict the presence of rice crops at a given location using satellite data. This is achieved by developing a rice crop classification model, which can distinguish between rice and non-rice fields. 
</p>

<p align="justify">In this Project the model has been built to predict rice crops against non-rice crops (which might include forest, other vegetation and water bodies) using features from the Sentinel-1 Radiometrically Terrain Corrected (RTC)  dataset as predictor variables. In this demonstration, i have used two features from the Sentinel-1 dataset, namely VV (Vertical polarization – Vertical polarization) and VH (Vertical polarization – Horizontal polarization) and trained a Random forest regression model with these features. I have extracted the VV band and VH band data from the Sentinel-1 dataset for the period of one year for a given location.

Most of the functions presented in this project were adapted from the <a href="https://planetarycomputer.microsoft.com/dataset/sentinel-1-rtc#Example-Notebook">Sentinel-1-RTC notebook</a> found in the Planetary Computer portal.</p>
    
