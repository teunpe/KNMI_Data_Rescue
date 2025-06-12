Repository for the Data Engineering course
==========================================
This repository contains rescued data, digitized from old weather tables. Part of the data is from KNMI data rescue efforts, in relatively unprocessed format. An example image of an original weather table archived at the KNMI is included. Another part is from the data rescue of the Holyoke & Wigglesworth meteorological diaries, accessible [here](https://crudata.uea.ac.uk/cru/data/holyoke/).

KNMI data is to be processed into SEF, so that it can be included in existing datasets used in climate models. Additionally, data should be formatted for use in table recognition models to digitize other KNMI data. 
### Structure:

    .
    ├── data/                         
    │   ├── CSVs/                   # Output location of CSV conversion
    │   ├── digitized/              # Raw data from KNMI archive
    │   ├── Holyoke/                # Raw Holyoke data
    │   ├── Wigglesworth/           # Raw Wigglesworth data
    ├── dbs/                        # Processed Parquet files
    ├── images/                     # Example images
    ├── holyoke_data.ipynb          # Processing of Holyoke data
    ├── knmi_data.ipynb             # Processing of KNMI data
    ├── Oranjestad_Precip.tsv       # Example SEF output
    ├── README.md                    
    ├── sef_conversion.ipynb        # Example functions for SEF conversion
    ├── training_data_prep.ipynb    # Example function for training data preparation
    └── wigglesworth_data.ipynb     # Processing of Wigglesworth data 

### Countries with scans of original tables:
- Bonaire
- Willemstad
