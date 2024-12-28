README

Project Title: Macrobenthic Invertebrate Distribution & Abundance in the Thames Estuary

About

This study aims to provide a comprehensive overview of the relationship between microbenthic taxa distributions sampled from sites within the Thames Estuary and investigates changes in abundance patterns.

Installations
The required dataset, project information and coding script can be downloaded from the GitHub repository: https://github.com/Rosie-Ann-Rickward/SWBio_2024   
This folder contains:
* The Jupyter notebook: Final_Project.ipynb
* The final data file: subset_benthic.csv (this is a large file so can be accessed using .gitattributes)
* (note this file was made by merging the marine benthic invertebrate dataset collected by the Environmental Agency: https://environment.data.gov.uk/ecology/explorer/downloads/TC_BENT_OPEN_DATA_TAXA.zip with the Biosys Taxon Info sheet: https://environment.data.gov.uk/ecology/explorer/downloads/OPEN_DATA_TAXON_INFO.zip )
* The two page report: Brief_Report

* The shapefile needed for mapping the Thames Estuary: gis_osm_water_a_free_1.shp can be extracted from the england-latest-free.shp.zip                                        
* (note: this folder was downloaded from Geofabrik: https://download.geofssabrik.de/europe/united-kingdom/england-latest-free.shp.zip/gis_osm_water_a_free_1.shp)
* This file was too large even for Git LFS so user will have to download, extract and save files to their own working directory.

Subset_benthic.csv Column Descriptions for Analysis   
* SEA_AREA - Sea Area in Biosys, free-text field (e.g. LIVERPOOL BAY)
* SITE_FULL_EASTING - Full Easting of the site (e.g. 258450) for the site.
* SITE_FULL_NORTHING - Full Northing of the site (e.g. 103430) for the site.
* SITE_NGR_10_FIG - Ten-digit National Grid Reference (e.g. SS5845003430) for the site.
* SAMPLE_DATE - Date the sample was taken (e.g. 05/05/1994)
* YEAR – New column made from extracting year from SAMPLE_DATE
* NUMBER_FOUND- Number of individuals found
* TAXON_LIST_ITEM_KEY- This is a unique ID, assigned by the NHM, to each name in the EA checklist. This code is required by Biosys
* TAXON_GROUP_NAME - Name of the taxon group
 For further information and definitions of columns not used in this analysis see: https://environment.data.gov.uk/api/file/download?fileDataSetId=c18bf8b1-8ea3-4827-8a84-2e21fc5ede4b&fileName=Marine_benthic_invertebrate_surveys_(Biosys).pdf 
Support information
Any issues or queries can be raised by contacting rr395@exeter.ac.uk


