<img src="https://github.com/a-vishniavetski/google-location-history/assets/132013288/ddd1dd25-f45c-4966-bc30-c2826f2070cc" align="right" height="170"></img>

# Google's "Location History" Data Analysis
> _With Pandas, Matplotlib and Jupyter Notebook._
> 
> _The source code is located in the `Location History.ipynb` file._

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Navigation

- [Overview](#overview)
- [Visualizations](#Visualizations)
- [Statistics](#Statistics)
- [Conclusion](#Conclusion)

## Overview

This project utilizes six months of geolocation data collected by Google (67,000 entries) to analyze user's (mine) movements and activities. 

Employing Pandas library the data is processed to extract key information, such as:
* longitude
* latitude
* timestamp
* altitude
* probable activity the user (me) was undertaking

Using this information it is possible to plot my locations on a map, depicting where and when I've been, using Matplotlib, Geopandas, and Shapely, as well as to analyze the observation frequencies, activity frequencies, and altitude history.

## Visualizations
### _Color gradients are employed to indicate the recency of each location. Yellow points are the newest dates, dark blue points are the oldest dates._

![europe][europe]

![poland][poland]

![city][city]

![world][world]

## Statistics

![observations][observations]

![most_obs_day][most_obs_day]

![altitude_hist][altitude_hist]

![altitude][altitude]

## Conclusion

It is better to see something once than to hear about it a hundred times, and exploration of the aforementioned data allowes us to visualise just _how much_ information about us Google collects and what detailed inferences he can produce from it. 

While exciting, it motivated me to turn _off_ my geolocation data in my Google Account, even though I won't be able to use it for data analysis anymore.

[europe]: https://github.com/a-vishniavetski/google-location-history/blob/main/output/europe.png "Europe"
[poland]: https://github.com/a-vishniavetski/google-location-history/blob/main/output/poland.png "Poland"
[city]: https://github.com/a-vishniavetski/google-location-history/assets/132013288/b6b931b8-48c4-44e6-8d04-51d87e6bf73c "City"
[world]: https://github.com/a-vishniavetski/google-location-history/blob/main/output/world.png
[observations]: https://github.com/a-vishniavetski/google-location-history/blob/main/output/observations.png "Observations"
[most_obs_day]: https://github.com/a-vishniavetski/google-location-history/blob/main/output/most_obs_day.png "Most observed day"
[altitude_hist]: https://github.com/a-vishniavetski/google-location-history/blob/main/output/altitude_hist.png "Altitude histogram"
[altitude]: https://github.com/a-vishniavetski/google-location-history/blob/main/output/altitude.png "Altitude"
