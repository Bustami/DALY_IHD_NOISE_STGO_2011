# DALY_IHD_NOISE_STGO_2011
The R programming code used in paper "Influence of road traffic noise in ischaemic heart disease. Introduction to the issue in Santiago of Chile" (Inter Noise 2015: http://internoise2015.com/) 

This code processed the data from the Department of Health Statistics and Information of Ministry of Health of Chile, specifically the 2011 data of diagnosis associated to ischaemic heart diseases (IHD) in Santiago of Chile and the dead people caused by it. The data can be downloaded from this site:  http://www.deis.cl/?p=1020

The code takes in account the following codes and information:
* International Classification of Diseases of 2010 (ICD-10) for IHD: I20 to I25
* Unique Territorial Code for studied area (32 communes of Santiago, Puente Alto & San Bernardo): 13101 - 13132, 13201 and 13401
* The Life Expectancy by gender downloaded from this site: http://www.deis.cl/?page_id=683
* The Disability Weight (DW) value suggested to IHD = 0.35
* The Population Attributable Fraction (PAF) calculated for IHD and road traffic noise in Santiago of Chile in 2011: 0.039715
