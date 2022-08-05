# Sentinel 1 Level 0 Decoding Demo

This Jupyter notebook demonstrates data decoding and subsequent example image formation from Sentinel-1 Level 0 files using my [sentinel1decoder python package](https://github.com/Rich-Hall/sentinel1decoder/tree/main/sentinel1decoder). It is available to view on [nbviewer.org here](https://nbviewer.org/github/Rich-Hall/sentinel1Level0DecodingDemo/blob/main/sentinel1Level0DecodingDemo.ipynb).


## A note on data
Sentinel-1 Level 0 files are typically too large to reside on github - the file used in the example is 727MB, against github's upload limit of 100MB. It is therefore assumed that the user has downloaded their own data, likely from ESA's [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/home).

The particular stripmap data take used in the example was acquired on 10-July-2022 over Sao Paulo by Sentinel-1A. The search term "S1A_S3_RAW__0SDH_20220710T213600_20220710T213625_044043_0541DB_56CE" (without the quotes) on the Copernicus site should find this product. A user account will be required to download the data, and the user will need to unzip the archive once downloaded. The very long folder names retained in the archive's file structure tend to produce problems, so it is assumed the .dat files inside the archive are then placed in the data/sao_paulo folder directly (without being renamed).
