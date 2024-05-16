# Analysis of daily snow depth data from DWD

This repository provides a notebook which contains:
1. A collection of small simple functions to download and parse daily DWD station data from opendata.dwd.de (quickly developed to not have to relly on the nice but a bit complex package `wetterdienst` which unfortunately does not play nice with recent pandas versions anymore)
2. An analysis of the evolution of snow depth data for an individual station over the last decades

Note that the measurement devices have changed over time (all info is also on opendata.dwd.de), which might have affeceted the measurements taken. But the difference between manual and automated daily snow height observations should not be that large.

Results for the DWD station in Garmisch-Partenkirchen look like this

<img width="800" alt="Bildschirmfoto 2024-05-16 um 23 11 32" src="https://github.com/cchwala/dwd_snow_data_analysis/assets/102827/f57123e7-9fd5-4def-8d9c-fafa8abd599c">

<img width="800" alt="Bildschirmfoto 2024-05-16 um 23 12 10" src="https://github.com/cchwala/dwd_snow_data_analysis/assets/102827/67fdfd61-8dfa-4506-929b-be2253e284ab">

<img width="850" alt="Bildschirmfoto 2024-05-16 um 23 12 31" src="https://github.com/cchwala/dwd_snow_data_analysis/assets/102827/185d65d5-fe88-409c-9083-e7ebc819a603">
