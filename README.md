This folder contains the supplementary data for:

Stahl MO, Gehring J, Jameel Y. 2020. Isotopic variation in groundwater across the conterminous US – insight into hydrologic processes. Hydrological Processes: hyp.13832 DOI: 10.1002/hyp.13832


Raster files containing the δ2H and δ18O groundwater isoscapes and related files listed below
•	RF_model_GW_isotopes_H.grd
•	RF_model_GW_isotopes_O.grd
•	RF_model_GW_isotopes_H.gri
•	RF_model_GW_isotopes_O.gri
•	randomforest_and_isoscape.Rmd

The file randomforest_and_isoscape.Rmd has R code to load in the isoscapes and the random forest model objects (R files RF_d2H.rds and RF_d18O.rds, which are included in the supplementary files)

Note, when loading in the raster (.grd) files you must have the .gri file in the same directory.
The file gw_data.csv has the groundwater stable water isotope samples compiled for this study along with the spatial and environmental attributes described in the main text Table 1.
