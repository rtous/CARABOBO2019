# CARABOBO2019 dataset

## Description

This repository contains the CARABOBO19 dataset, consisting of three-channel continuous data recorded by the broadband stations of the Venezuelan Foundation of Seismological Research (FUNVISIS) in the region of 9.5 to 11.5&deg;N and 67.0 to 69.0&deg;W during the time period from April 2018 to April 2019. During this period, 949 earthquakes were recorded in that area. A detailed description of the data can be found in the research paper mentioned in the [Acknowledgments](#Acknowledgements) section.

## Files

 The data (both the files with the waveforms and the metadata) comes from [SEISAN](https://www.geosig.com/files/GS_SEISAN_9_0_1.pdf), a seismic analysis software suite.



### Waveforms (.mseed files)

The waveforms containg the P-arrivals of the earthquakes can be found in the "mseed" folder:

* Each .mseed file contains three channel waveforms in miniSEED format and sampled at 100Hz.
* Each .mseed file contains waveforms from just one station.


### Metadata (catalog)

The analyst-labeled P-wave arrivals related to the 949 earthquakes can be found in different formats:

* JSON format (catalog.json)
* Nordic format (sfiles_nordicformat directory)
* Raw SEISAN files (original data also in Nordic format)

Just pick one of the three alternatives as they contain the same information. 

## Acknowledgements

If you find this repository useful for your research, please cite the original publication:


	@article{Tous2020,
	    author = {R. Tous and L. Alvarado and B. Otero and L. Cruz and O. Rojas},
	    title = {Deep Neural Networks for Earthquake Detection and Source Region Estimation in North Central Venezuela},
	    journal = {Bulletin of the Seismological Society of America},
	    number = {?},
	    pages = {?--?},
	    volume = {?},
	    year = {2020}
	}