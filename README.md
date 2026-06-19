# GroundDislocation Dataset

## Overview

A list of twenty-three earthquakes that occurred in the broader Greek area in 2020 was constructed using data retrieved from the USGS Search Earthquake Catalog. The selected events had magnitudes spanning from 3.0 to 5.9, include in Table 1. For each earthquake, Sentinel-1 satellite synthetic aperture radar (SAR) images of level 1 Single Look Complex (SLC) (Interferometric Wide (IW) swath mode of resolution IW_SLC_1S) were used. The SAR images were for five six-day intervals before the occurrence of the earthquake. The last image was recorded a couple of hours to four days before the earthquake, depending on the availability of images in the database. 

---

## Earthquakes Included
A list of the 23 earthquakes used in this study. Latitude and longitude are in decimal degrees ranging from 0° to 180°. The timestamp is in Coordinated Universal Time (UTC) format, with the date at the beginning and the time in hours, minutes and seconds, with the letters ‘T’ and ‘Z’ indicating the UTC format.

| # | Date and Time (UTC) | Latitude | Longitude | Magnitude | Scale | Location |
|---|---------------------|----------|-----------|-----------|-------|----------|
| 1 | 2020-05-11T09:33:07Z | 37.824 | 27.144 | 3.0 | ml | 10 km WSW of Kusadasi |
| 2 | 2020-06-01T23:15:01Z | 40.459 | 21.483 | 3.2 | ml | 7 km WSW of Emporio |
| 3 | 2020-04-13T23:56:37Z | 41.603 | 28.747 | 3.3 | ml | 33 km N of Durusu |
| 4 | 2020-02-20T00:32:32Z | 35.272 | 23.962 | 3.6 | mb | 17 km WNW of Chora Sfakion |
| 5 | 2020-10-30T12:41:31Z | 37.797 | 26.977 | 4.0 | mb | 4 km N of Samos |
| 6 | 2020-04-18T23:36:53Z | 38.073 | 20.321 | 4.1 | mb | 17 km SW of Lixouri |
| 7 | 2020-10-17T20:31:59Z | 39.108 | 23.415 | 4.2 | mb | 8 km SW of Skiathos |
| 8 | 2020-07-07T15:19:51Z | 38.836 | 25.331 | 4.3 | mb | 38 km NNW of Psara |
| 9 | 2020-06-04T04:51:18Z | 35.089 | 26.052 | 4.4 | mb | 14 km SSW of Sitia |
| 10 | 2020-02-04T16:47:10Z | 38.997 | 27.941 | 4.5 | mb | 12 km NE of Akhisar |
| 11 | 2020-10-30T09:20:36Z | 34.401 | 26.428 | 4.6 | mb | 89 km S of Palekastro |
| 12 | 2020-02-06T09:24:16Z | 39.254 | 21.497 | 4.7 | mwr | 10 km SSE of Anthiro |
| 13 | 2020-02-18T16:09:23Z | 39.107 | 27.817 | 4.8 | mb | 12 km E of Kirkagac |
| 14 | 2020-12-29T08:06:09Z | 34.709 | 24.069 | 4.9 | mb | 14 km S of Kastri |
| 15 | 2020-08-17T07:27:02Z | 36.897 | 23.770 | 5.0 | mww | 56 km SSE of Hydra |
| 16 | 2020-05-22T03:40:30Z | 34.483 | 25.886 | 5.1 | mww | 60 km SSE of Ierapetra |
| 17 | 2020-10-12T04:11:27Z | 35.644 | 26.246 | 5.2 | mww | 49 km N of Palekastro |
| 18 | 2020-10-30T15:14:55Z | 37.831 | 26.822 | 5.3 | mww | 8 km NW of Kokkari |
| 19 | 2020-09-26T22:50:25Z | 39.984 | 24.334 | 5.4 | mww | 31 km SSE of Karyes |
| 20 | 2020-01-28T15:38:34Z | 35.218 | 27.891 | 5.5 | mww | 69 km ESE of Karpathos |
| 21 | 2020-01-22T19:22:16Z | 39.072 | 27.838 | 5.6 | mww | 15 km ESE of Kirkagac |
| 22 | 2020-05-20T23:43:16Z | 35.159 | 20.277 | 5.7 | mww | 224 km SW of Methoni |
| 23 | 2020-09-18T16:28:17Z | 35.036 | 25.303 | 5.9 | mww | 12 km SSE of Arkalochori |

---

InSAR was employed to generate four interferograms for each earthquake from the five SAR images, using the Sentinel Application Platform (SNAP) Sentinel Toolbox of the European Space Agency and according to the instructions provided by the ESA. 
All dislocation images were cropped into 100 × 100-pixel-size rectangles with the epicenter of each earthquake in their center. Ground displacement images were generated from the InSAR interferograms. 
The cropped images were divided into two classes. One class comprised smaller earthquakes of magnitude 3.0 to 4.6 Mw, and the other contained larger earthquakes of 4.7 to 5.9 Mw.
The Ground Dislocation dataset includes 92 images in total, divided into two classes.

## Citation

If you use this dataset in your research, please cite the original publication:

```bibtex
@article{Chariskou2026,
  author = {Chariskou, C. and Vrochidou, E. and Papakostas, George A.},
  title = {Pre-Seismic Ground Dislocations from Interferometric Satellite Synthetic Aperture Radar Images as Predictors of Earthquake Magnitude and Epicenter Localization},
  journal = {Applied Sciences},
  year = {2026}
}
```
