# geodev-lab-project-Week2
This dataset contains recorded oil spill incidents in Nigeria, extracted from the National Oil Spill Detection and Response Agency (NOSDRA) Oil Spill Monitor, the official public platform for reported oil spill information in Nigeria. The dataset covers incidents recorded between 2015 and 2025 and is used for geospatial analysis of oil spill patterns across Nigeria's South South region.

The original NOSDRA extract contained 10,047 records and 42 fields. Following data cleaning, validation, removal of malformed records, and preparation for analysis, the working dataset contains 9,279 oil spill incident records.

Key Data Fields

The dataset contains information relating to:

Incident date and report date
State and Local Government Area (LGA)
Latitude and longitude
Operating company
Cause of spill
Facility type
Contaminant
Estimated spill quantity
Quantity recovered
Estimated spill area
Spill-area habitat
Environmental impact information
NOSDRA incident identifiers and status information

These variables support spatial, temporal, statistical, and geospatial analysis of oil spill incidents.

Data Quality

The dataset has undergone preprocessing to improve its suitability for geospatial analysis. This includes validation of geographic coordinates, standardisation of selected fields, date processing, handling of missing values, and removal of malformed records.

However, the dataset retains limitations associated with the original source. Some records contain missing geographic, quantity, or other attribute information. Coordinate errors or inconsistencies may also occur in reported incident records. Therefore, users should validate and appropriately filter the data before conducting analysis.

The dataset represents reported and recorded oil spill incidents and should not be interpreted as a complete record of every oil spill occurrence in Nigeria.

Source

National Oil Spill Detection and Response Agency (NOSDRA) – Oil Spill Monitor

The original data source is publicly accessible through the NOSDRA Oil Spill Monitor.

Purpose

This dataset is provided for educational, research, GIS, geospatial analytics, data science, and environmental analysis. It supports the development of oil spill hotspot maps, spatial distribution analysis, temporal trend analysis, environmental risk assessment, and interactive geospatial dashboards.

For this project, the dataset is specifically used to investigate the spatial distribution and concentration of oil spill incidents across Nigeria's South South region.
