# ThermoSuite
ThermoSuite offers a set of tools with the ability of analyzing dynamic thermal video data.

Methods used and results obtained are presented in [1]. 

Video data in the sub-folders is related to the results presented in [1]. Dynamic thermal data from human participants left and right feet as well as 
dynamic thermal data from a static object was captured.  Specifically, dynamic thermal data recording of a leather ball, with emissivity = 0.95, was 
obtained.  

The aim with the capture of the data on the leather ball was to simulate the recording of the data from human feet on an object whose temperature 
variations are known. More information regarding the acquisition protocol and the methods of analysis are available in the manuscript. 

The data was analysed using Principal Component Analysis (PCA) to determine and identify different processes which affect the overall temperature 
variations observed through thermal imaging. The first three computed components from the leather ball as well as the human feet are available in 
Figure 1 and Figure 2 in Figures folder respectively as well as the manuscript. 


Available data: 

Manuscript Figures - Manuscript figures published in [1].
Subjects Data - Physiological and categorical data of the participants acquired for the study.
Control 01 - Thermal data of static leather ball presented in [1]. 
Subject XX - Thermal data of plantar aspect of human feet. Subject 01 (Left) presented in [1]. 

For each of Control 01 and Subject XX subfolders a number of videos are present: 
 - Components - Plot of principal components (Top) together with the corresponding weights matrix (Bottom) and percentage of variance explained.
 - Original video - Original video for dynamic thermal acquisition.
 - Reconstruction 1 - Reconstruction of data without component describing change in background temperature.
 - Reconstruction 2 - Reconstruction of data without component describing process of warming of ball surface representative of physiological process or 
		      physiological process in case of feet. 
 - Reconstruction 3 - Reconstruction of first principal component only.
 - Reconstruction 4 - Reconstruction of second principal component only.
 - Reconstruction 5 - Reconstruction of third principal component only.

References 
[1] J. Gauci, K. Camilleri, O. Falzon, "Principal Component Analysis for Dynamic Thermal Video Analysis"
