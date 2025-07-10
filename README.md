# Final-Project

### Our research aims to use PCA method to develop a new heat vulnerability index (called NHVI) based on three factors: original HVI derived by nyc.gov environmental health department, household air conditioner percentage, and cooling feature counts. The distribution of NHVI will be plotted on the map of the New York City to show the spatial inequalities between communities.


## Link to relevent datasets: 
(1): Air conditioner data: New York City Department of Health, Environment & Health Data Portal. Climate data. Household air conditioning. Accessed at https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/climate/?id=2185 on 07/02/2025.

(2): HVI data: New York City Department of Health, Environment & Health Data Portal. Climate data. Heat vulnerability index (NTA). Accessed at https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/climate/?id=2191 on 07/02/2025.

(3): Cooling features: 
https://data.cityofnewyork.us/dataset/Cool-It-NYC-2020-Cooling-Sites/h2bn-gu9k/about_data
https://data.cityofnewyork.us/dataset/Cool-It-NYC-2020-Drinking-Fountains/wxhr-qbhz/about_data
https://data.cityofnewyork.us/dataset/Cool-It-NYC-2020-Spray-Showers/tzuk-eq2f/about_data

(4): NTA (Neighborhood Tabulation Area): https://data.cityofnewyork.us/City-Government/2020-Neighborhood-Tabulation-Areas-NTAs-/9nt8-h7nd/about_data

(5): PUMA (Public Use Microdata Areas): https://data.cityofnewyork.us/City-Government/2020-Public-Use-Microdata-Areas-PUMAs-/pikk-p9nv/about_data


### Our research start with importing the datasets, after that, we will count the total number of cooling features across NTAs, we will plot out the locations of the cooling features. Then, we will transfer the AC percentage data documented in PUMA regime into NTA regime, we will make a barplot to visualize three indexes for different boroughs. Finally we will use the PCA approach to calculated NHVI (by the combination of AC%, cooling feature count, and original HVI) by NTA regime and make a map base on that; besides, we will create a biplot and loading map for each PC1 and PC2. 
