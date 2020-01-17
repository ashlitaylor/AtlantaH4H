-------------------------------------------------------------------------
# Geo-spatial and Market Analysis of Atlanta for the Habitat for Humanity
-------------------------------------------------------------------------
This scala code was completed as part of an assignment for my Data and Visual Analytics course at The Georgia Insitute of Technology. 

### Introduction
The Atlanta Habitat for Humanity is the third largest Habitat affiliate in America. The organization produces approximately 50 homes per year for it’s homeownership program, serving families that make between $30K to 50K per year. In 2018, they acquired 40 properties for this program. Significant increases in property costs in Fulton County have resulted in a decline of affordable properties that can be acquired. This necessitates statistical analysis of available properties to ascertain which regions should receive concentrated efforts for lot acquisition.  


Objectives:
-	Property analysis: identify parcels that meet Habitat’s criteria. 
-	Market analysis: identify neighborhoods or localized areas that we should prioritize that may become unattainable with-in the next 5 to 10 years. 

Budget and Parcel Parameters:
- Budget: $300K - $500K
- Lot cost: Under $40K (ideally)
- Flat
- Not on a major road
- On a paved road
- Not in a flood plain
- 75 ft away from a stream
- Not in College Park
- Lot frontage must be at least 50ft
- Lot depth much be at least 80ft
- No easements
- No sewer setback easements
- Sewer connection
- Not in a neighborhood association
- Sewer connection
- Not in a neighborhood association

### Data
- Fulton County Open GIS data
Over 300K records of available parcels in Fulton County
- Fulton County tax CAMA tables
- Tax parcel data from 2013 to 2018

Over 1.8 million records

### Prerequisites
##### Esri ArcGIS 
The mapping and anlysis was performed using GIS software on [ArcGIS online](https://www.esri.com/en-us/arcgis/products/arcgis-online/overview) however the layers can be processed using any comparable software.   

##### Time Series - R
The Time Series analysis was performed in the R programming language using RStudio, and can be run using any comparable integrated development environment for R.  


<!--### Run
To run the code on the bitcoinotc.csv edge file: 
1. Import the bitcoinotc.csv data into your data space on Databricks.
2. Import the BitcoinOTC.dbc notebook to your workspace on Databricks. 
3. Create a cluster.
4. Attach the cluster to the imported notebook.
5. Run all code cells.
6. Download the dataframe containing the most important nodes directly as a .csv file using the download button in the last cell. 
