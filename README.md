# Talend_slowing_changing_dimension
Extracting the data from various operational systems, transforming in talend and loading it into the data warehouse:
Steps involved:
1. Create a job in the Talend Open Studio for data integration
2. Create the metadata for the external files will contain the data of the business
3. Create the metadata for operational systems and dimensional table of the data warehouse
4. Extract the data from the external files, cleanse or transform the data and load it into the operational systems
5. From this OLAP systems load the data into the OLTP systems which is used for analytical purposes
6. In this project I used the concept called Slowly Changing Dimensions(SCD).
7. There are four types in SCD but in this project I only used one type which is SCD type-2.
