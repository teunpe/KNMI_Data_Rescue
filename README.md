Repository for the Data Engineering course
==========================================
This repository contains rescued data, digitized from old weather tables. Part of the data is from KNMI data rescue efforts, in relatively unprocessed format. An example image of an original weather table archived at the KNMI is included. Another part (not included in this repository, but available [here](https://github.com/C3S-Data-Rescue-Lot1-WP3/Rescued-Data)) is from other data rescue projects and has been formatted neatly into SEF ([Station Exchange Format](https://github.com/C3S-Data-Rescue-Lot1-WP3/SEF)). 

KNMI data is to be processed into SEF, so that it can be included in existing datasets used in climate models. Additionally, data should be formatted for use in table recognition models to digitize other KNMI data. 
### Structure:

    .
    ├── digitized                   # Raw data from KNMI archive
    ├── exploration.ipynb           # Brief exploration of raw data
    ├── knmi_data.ipynb             # Processing of KNMI data
    ├── README.md                    
    ├── sample_image.jpg            # Example of a table image
    └── sef_data.ipynb              # Processing of rescued data 

