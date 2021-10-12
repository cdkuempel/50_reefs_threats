# 50_reefs_threats

This repository accompanies the publication by Kuempel et al. 2021 Identifying management opportunities to combat climate, land, and marine threats across less climate exposed coral reefs in the journal Conservation Biology.

Repository structure
1. data

There are two main data folders: raw_data and output_data. Many of the data used in the analysis are large spatial files that take significant time to process. We recommend using a server or downloading the files directly from XXX.

2. scripts
There are XXX scripts that should be executed in sequential order as follows:

Download_pressure.Rmd - this script downloads the data layers for calculating 2013 cumulative impact (global, climate, land, marine) from the KNB repository. The data is based on publication the from Halpern et al. 2015.

Change_in_pressure.Rmd - this script downloads the data layers for calculating the change in cumulative impact (global, climate, land, marine) from the KNB repository. The data is based on the publication from Halpern et al. 2015. 

Reef_threats.Rmd - this script uses spatial data on the 50 bioclimatic units (BCUs) that are less-exposed to climate change and Exclusive Economic Zones to calculate the level of cumulative in pact (in 2013 and between 2008 and 2013) within BCUs and countries responsible for their management.

Reefs_WDPA.Rmd - this script calculates the amount of 50 reefs and coral reefs (based on WCMC coral reef layer) that are protected based on the World Database on Protected Areas.

Management_index.Rmd - this script calculates the management indices (climate, marine, land) for each country based on common metrics of conservation potential/commitment. 

4. figures

Figures 1 and 2 were created by BAS outside of the R programming language. Code to recreate Figures 3,4, and 5 can be found in the Figures.Rmd file. However, further editing was conducted in Adobe Illustrator by BAS for color scheme and final layout.
