# COAPS
Undergraduate Research Work at the Center of Oceanic and Atmospheric Prediction Studies 

(SAMOS) has been collecting, quality-evaluating, and distributing and archiving underway navigational, meteorological, and oceanographic observations from research vessels. This data is collecting ship and instrumental metadata and one-minute interval observations from 44 research vessels. Maps provide users with the geospatial coverage within the SAMOS dataset, with a focus on the Essential Climate/Ocean Variables, and recommendations are made regarding which versions of the dataset should be accessed by different user communities. 

The SAMOS initiative is designed to address the data needs within the air-sea interactions, satellite and remote-sensing, numerical modeling, and geoscience informatics communities.  Flux products can be used to evaluate numerical model flux fields. 

Acquiring SAMOS Data:

The SAMOS metadata specification is based on a combination of the metadata requirements from Voluntary Observing Ship Climate (VOSClim - (https://www.ncdc.noaa.gov/data-acce ss/marineocean-data/vosclim/ship-metadata) program and the International Comprehensive Ocean-Atmosphere Data Set. Key metadata requested for each vessel include the vessel name; call sign; International Maritime Organization number; operating country, name, and location of the operating institution; and contact information for the vessel operations manager and shipboard technicians.  Digital images are used to identify poorly exposed sensors and to provide feedback to the operator regarding relocating sensors to improve overall data quality. metadata requested for each physical device include the instrument manufacturer (make) and model number; units of observation; whether the value is measured or derived (e.g., dewpoint temperature is rarely measured but often derived from air temperature and relative humidity); whether the time stamp marks the beginning, middle, or end of the averaging period; the length of the average (in seconds); the raw data sampling rate (in Hz); the data precision; the date of instrument calibration; and the three‐dimensional position of the sensor on the vessel (measured back from the bow, port/starboard of the centreline, and above/below the plimsoll line). We also request the direction convention for the winds (to or from which the wind blows), the orientation of the anemometer zero line with respect to the bow whether the pressure value is adjusted to sea level, and the direction convention for all radiation measurements (upwelling, downwelling, or net). Once the metadata is received, they are loaded into a ship profile database where it can be tracked. 

DATA QUALITY EVALUATION:

SAMOS data QC begins with verifying that the original file came from a recruited vessel and is in the proper key– value format. 
Once verified, the data are converted to SI units (if necessary), checked for temporal sequence, and blended with ship and instrumental metadata (e.g., instrument height, units, sensor make/model) from the SAMOS database. 
This first netCDF version of the observations is not released to users until the data undergo automated QC to apply flags, resulting in a preliminary (version 100) file

ACCESSING & USING DATA

The primary archive for the SAMOS dataset is at NCEI (https://dx.doi.org/10.7289/V5QJ7F8R). Data can be accessed on the web by observation date at https://samos.coaps.fsu.edu/html/data_availability.php or by cruise identifier at https://samos.coaps.fsu.edu/html/crui se_data_availability.php . 
