# 50_reefs_threats

This repository accompanies the publication by Kuempel et al. 2021 Identifying management opportunities to combat climate, land, and marine threats across less climate exposed coral reefs in the journal Conservation Biology.

Repository structure
# 1. data

There are two main data folders: raw_data and output_data. Many of the data used in the analysis are large spatial files that take significant time to process. We recommend using a server or downloading the files directly from XXX.

# 2. scripts

There are seven scripts that should be executed in sequential order as follows:

  1. Download_pressure.Rmd - this script downloads the data layers for calculating 2013 cumulative impact (global, climate, land, marine) from the KNB repository. The data is based on publication the from Halpern et al. 2015.

  2. Change_in_pressure.Rmd - this script downloads the data layers for calculating the change in cumulative impact (global, climate, land, marine) from the KNB repository. The data is based on the publication from Halpern et al. 2015. 

  3. Reef_threats.Rmd - this script uses spatial data on the 50 bioclimatic units (BCUs) that are less-exposed to climate change and Exclusive Economic Zones to calculate the level of cumulative in pact (in 2013 and between 2008 and 2013) within BCUs and countries responsible for their management.

  4. Management_index.Rmd - this script calculates the management indices (climate, marine, land) for each country based on common metrics of conservation potential/commitment. 

  5. Results.Rmd - this script generates the results in the manuscript as well as other summary statistics based on the data created in the above scripts.

  6. Figures.Rmd - this script recreates several of the figures in the manuscript and supplemental materials. Note additional editing was done in Adobe Illustrator and powerpoint

  7. Supp_reef_iso3_threats.Rmd - this script re-calculates threats within individual BCUs within each country (Table S5)

# 4. figures

All figures created within scripts are saved within the figures folder.

Figure 1. This figure was created by BAS outside of the R programming language. The data to recreate this figure are noted in the Figure.Rmd script.

Figure 2. This figure was created by BAS outside of the R programming language. The data to recreate this figure are noted in the Figure.Rmd script.

Figure 3, 4, 5, S2, and S3 are created within the Figure.Rmd script. Significant editing was done by BAS in Adobe Illustrator for the final figures in the manuscript.

Figure S1. This figure is created within the Management_index.Rmd script. The figures are saved in the figure folder as Climate_corrplot.png, Marine_corrplot.png and Land_corrplot.png. Further editing was done in powerpoint.

Figure S4. This figure is created in the script Supp_boxplot_figure.Rmd.


