# Nasa Harvest Rwanda Field Boundary Detection Challenge Tutorial

This folder contains a notebook tutorial for the Nasa Harvest Rwanda field boundary detection competition [Nasa Harvest Field Boundary detection Challenge](https://zindi.africa/competitions/nasa-harvest-field-boundary-detection-challenge). 

The dataset contains field boundaries for smallholder farms in eastern Rwanda. The Nasa Harvest program funded a team of annotators from TaQadam to label Planet imagery for the 2021 growing season for the purpose of conducting the Rwanda Field boundary detection Challenge. The dataset includes rasterized labeled field boundaries and time series satellite imagery from Planet's NICFI program. Planet's basemap imagery is provided for six months (March, April, August, October, November and December). The paired dataset is provided in 256x256 chips for a total of 70 tiles covering 1532 individual fields.

The starter notebook focuses on a baseline model using UNet to walk you through the process of loading and structuring the data, training the model, and exporting the predictions to the sample CSV file.

## Environment
The notebook `Nasa_Harvest_Model_MLHub.ipynb` can be run locally using the `requirements.txt` file on Python 3.8.13 with minimum RAM : 8GB

There is a version of the same notebook on google colaboratory [Google Colab](https://colab.research.google.com/gist/magabenza/f73b79da065913cdbbcdb080bc1d2be9/nasa_harvest_model_mlhub_colab.ipynb)

## Competition Organizers
### About Radiant Earth Foundation ([radiant.earth](https://radiant.earth))
![Radiant Earth Foundation Logo](/images/ref.png)

Radiant Earth Foundation is a nonprofit corporation working to empower organizations and individuals with open machine learning (ML) and Earth observation data, standards, and tools to address the world’s most critical international development challenges. Radiant Earth fosters collaboration through a cloud-based open geospatial training data library, Radiant MLHub. Radiant also supports an ecosystem of practitioners to develop standards, expand interoperability around ML on Earth observation, and provide information and training to help advance the capacity of those working in the global development sector using ML and Earth observation. Visit Radiant Earth on Twitter, LinkedIn, Medium, and GitHub.
### About University of Maryland, Nasa Harvest ([nasaharvest.org](https://nasaharvest.org/))
![umd Logo](/images/umd.png)
![Nasa Harvest Logo](/images/harvest.png)

NASA Harvest is NASA’s Food Security and Agriculture program based at the University of Maryland. NASA Harvest’s mission is to enable and advance the adoption of satellite Earth observations by public and private organizations to benefit food security, agriculture, and human and environmental resiliency in the US and worldwide. They accomplish this through a multidisciplinary and multisectoral Consortium of leading scientists and agricultural stakeholders at the University of Maryland and implement it together with partners across the globe. Visit NASA Harvest on [Twitter](https://twitter.com/HarvestProgram) and [Github](https://github.com/nasaharvest/).

## Competition Sponsor
### About USDA([fas.usda.gov](https://www.fas.usda.gov))
![usda Logo](/images/usda.png)

### About USAID([usaid.gov](https://www.usaid.gov/))
![usaid Logo](/images/usaid.png)

This challenge and the training dataset collection and curation are based upon work by NASA Harvest supported by USDA-Foreign Agricultural Service and USAID, under Award Number FX22TA10960R004 and Project Title Earth Observations for Field Level Agricultural Resource Mapping (EO-Farm): Pilot in Rwanda in Support of NISR. 


