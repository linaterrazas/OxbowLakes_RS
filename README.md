README

Title of data set: GEE_AreaWTLake.rar
Author: Terrazas-Villarroel Lina G.
Affiliations: 
TU Delft, Water management department
IHE Delft, Department of Water Resources and Ecosystems
Contact information (permanent): linaterrazas@gmail.com

1.	Introductory information

The compressed file "GEE_AreaWTLake.rar" contains area results of water type and land cover classification for 40 oxbow lakes in the Beni River in Bolivia, as part of the PhD Thesis of Lina G. Terrazas Villarroel.

2.	Methodological information

Analysis: Land cover and water type classification were evaluated in the region of each oxbow lake using Google Earth Engine and a random forest algorithm.

Quality control: in addition to double cloud filter applied before the classification, images with remaining haze, sparse clouds, or shadows were manually identified and removed to enhance data quality

Methods are described in publication “Monitoring oxbow lakes with remote sensing: Insights into turbidity, connectivity, and fish habitat”.

3.	Data specific information
Each csv file for each lake indicates a table with the following columns: 

Column, type, unit, description
Date, chr, [-], date of Landsat 7 ETM+ satellite image
Per_cloud, num, %, percentage of cloud coverage in the region of oxbow lake 
Vegetation, num, [sqkm], area of vegetation land cover type the region of oxbow lake 
Sediment, num, [sqkm], area of sediment land cover type the region of oxbow lake
WTO, num, [sqkm], area of WTO water type the region of oxbow lake 
WTA, num, [sqkm], area of WTA water type the region of oxbow lake
WTB, num, [sqkm], area of WTB water type the region of oxbow lake
WTC, num, [sqkm], area of WTC water type the region of oxbow lake
WTD, num, [sqkm], area of WTD water type the region of oxbow lake

No data: NA 

4.	Sharing and access information
Creative commons licenses: CC BY-NC

