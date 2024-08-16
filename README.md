# Microsnow for Radar module.

## Description

SnowEx is a program designed to relate in-situ snow measurements to satellite so that we can assess snow physical properties and variability over a larger spatial and temporal resolution. As of current, we are pretty limited in what we can quantify using optical and radar satellite imagery. Mainly, we are able to just see if snow is present (given the different reflectance and pixel brightness), but not properties within the snowpack. And given how variable snow is in the Western US, this necessitates the usage of snow assessment over the season and over a longer temporal record. The long-term objective with using snow microstructure (Micro-CT), and the primary objective of the 2020 SnowEx campaign, is 1) to test and validate snow water equivalant (SWE) retrieval from active and passive microwave sensors, and 2) to quantify variability within pixels of thermal infrared signatures to assess the value of kilometer-scale satellite infrared observations for snow energy balance modeling.

This module is designed to provide participants with resources using the NSIDC data respository, along with data comparisons and analysis for 3-5 sites in Grand Mesa, CO in during the 2020 SNowEx campaign. These sites have overlapping microstructure, snow-pit, snow penetrometer (SMP), laser, and SWESARR brightness temperature, which make it an ideal first step to advancements in the SnowEx program.

## Description of Data 
######  *(mainly pulled from NSIDC overviews)*

**Microsctucture:** Snow microstructure is processed using microcomputed tomography (micro-CT). Containers of snow were collected at 6 snow pits in approximately 17 cm intervals. There were approximately 5-8 discrete containers per pit and each container had an ~2 cm overlap with the sample below. A 6-cm section of snow was dissected from each container of snow, which were analyzed in ~2 cm sub-sections. Each sub-section was scanned in three intervals using a micro-CT instrument. The three interval scans comprise multiple slices, and were combined into the reconstructed final scan used for calculating the snow microstructural data.

This is the "golden standard" method and a key component of this module (etc etc)

**Snow-pit:** Snow-pits were dug and collected in Grand Mesa during the 2020 field season (between 27 January and 12 February 2020). The main parameters for this data set are snow temperature, snow depth, snow density, snow stratigraphy, snow grain size, liquid water content, and snow water equivalent. In addition to data files, this data set also contains site photos from each snow pit.

*NOTE:* each data parameter is saved as a separate .csv file. Make sure to download each .csv per site before running code.

**SMP:** This data set contains raw penetration force profiles from the SnowEx 2020 Intensive Observation Period in Grand Mesa, Colorado. Measurements were taken using the SnowMicroPen (SMP), a digital snow penetrometer. The data files contain force measurements (in Newtons) at various snow depths. Data are available from 28 January 2020 through 12 February 2020.

*NOTE:* SMP profiles were taken in a cross pattern around the central location, therefore there are numerous files per each site. It is recommended when downloading each file to use CTRL+F and search by site number to ensure no files are missed.

**Laser:** This data set contains vertical profiles of snow reflectance, specific surface area (SSA), and spherical equivalent snow grain diameter. Data were collected during the SnowEx 2020 Grand Mesa, Colorado Intensive Observation Period between 27 January and 12 February 2020. Reflectance was measured at snow pits using one of two integrating sphere laser devices, IRIS (InfraRed IntegraXng Sphere) or IceCube. SSA and spherical equivalent diameter were then derived from reflectance.

**SWESARR brightness temperature:** 
This data set contains airborne microwave brightness temperature observations from the Goddard Space Flight Center SWESARR (Snow Water Equivalent Synthetic Aperture Radar and Radiometer) instrument during the winter (10-12 February 2020) NASA SnowEx 2020 campaign at Grand Mesa, CO. Observations were made at three frequencies (10.65, 18.7, and 36.5 GHz; referred to as X, K, and Ka bands, respectively), at horizontal polarization with a nominal 45-degree look angle. 

## Tasks

#### 1. Using Matlab, call in data parameters (...)

#### 2. Do *XYZ*

#### 3. Do *XYZ*

#### 4. Do *XYZ*

#### 5. Do *XYZ*

#### 6. Do *XYZ*

#### 7. Do *XYZ*

#### 8. Do *XYZ*

#### 9. Do *XYZ*

#### 10. Do *XYZ*


## Resources for Data Download
#### Numerical Data
[NSIDC Main Data Page](https://nsidc.org/data/snowex/data)
- [Snow Microstructure Data](https://nsidc.org/data/snex20_gm_ctsm/versions/1)
- [Snow-Pit Data](https://nsidc.org/data/snex20_gm_sp/versions/1)
- [Snow Penetrometer (SMP) Data](https://nsidc.org/data/snex20_smp/versions/1)
- [Laser Data](https://nsidc.org/data/snex20_ssa/versions/1)

#### Microwave Radar
- [SWESARR Brightness Temperature](https://nsidc.org/data/data-access-tool/SNEX20_SWESARR_TB/versions/1).

## Using Matlab Functions

Within the Github, there are XX functions and XX corresponding codes that call in the functions and plot the data, as a first step to analsysis. The functions' jobs are to structure the data using information found in the filenames (i.e., site number, date of data collection, and file location where all of the data is saved to). For more help with using Matlab, Mathworks has a super helpful community and are open to any questions if you cannot already find the answer to your question(s): 

- [Syntax help](https://www.mathworks.com/help/matlab/)


- [Questions](https://www.mathworks.com/support/search.html?fq%5B%5D=asset_type_name:answer&fq%5B%5D=category:matlab/index&page=1&s_tid=CRUX_topnav)
