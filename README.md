# MIT805-Semester-Project-Assignment
New York City, one of the most popular cities in the US, has millions of taxi trips recorded hourly and shared monthly. This analysis aims to make quantitative analysis and provide understanding of the taxi trip data to assist with better trip planning and efficiency. The analysis will help locate hot-spot areas, busy durations as well as areas with low taxi resources.

# Dependancies
Language: python

Libraries: pandas, pyarrow, requests, tqdm, numpy, botocore, geopandas, meteostat, pyspark, matplotlib


# Datasets

[TLC Trip Record Data (From Jan 2023 to Dec 2024)](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

[Taxi Zone Lookup Table ](https://d37ci6vzurychx.cloudfront.net/misc/taxi_zone_lookup.csv)

[Meteostat Hourly Weather Data (from Jan 2023 to Dec 2024](https://dev.meteostat.net/python/hourly.html#example)



To download all the data, please locate download_data.ipynb notebook included in code, and run it.

The notebook downloads from from TLC’s official site,  it skip re-downloads using filename+size checksum. 
To run the experiment including, downloading all the data, mapreduce, and visualization, use NYC_Transport_MapReduce_Visualization.ipynb notebook. 
You can it locally or on Google colab (preferd option).
It downlods transport data from TLC’s official site, Normalize the data, run mapreduce functions and show visualization. No need to intsall anything if you run from google colab, all packages to be used will installed automatically.

# Directories
TCL Trip data will downloaded into \data\tlc

Hourly weather folder: \data\weather\hourly

Zone lookup and shape file: \data\geo

Please note that /data/ folder is included in .gitignore therefore it will note be part of the online repo, exists locally only.
