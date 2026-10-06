# Peak Forecast · Colorado

Mountain weather for Colorado ski areas, all 58 14ers, and 65 popular 13ers. Each spot is forecast at the summit, mid-mountain, and base/trailhead elevations.

- **Forecast:** median of 6 models (NOAA HRRR, NWS National Blend, GFS, ECMWF IFS, DWD ICON, CMC GEM) via [Open-Meteo](https://open-meteo.com), with the model spread shown as the range.
- **Official:** NWS gridded forecast, text forecast, and active alerts from [api.weather.gov](https://api.weather.gov).
- **Snowpack:** measured SWE and snow depth from the nearest USDA NRCS SNOTEL stations, compared with the 1991–2020 median.
- **Sharing:** copyable text summary and a downloadable forecast image.

Summit coordinates were checked against the USGS 3DEP 10 m elevation model. Everything runs in the browser from a single `index.html`, with no API keys or server.

Forecasts are guidance, not guarantees. For backcountry travel, check [CAIC](https://avalanche.state.co.us).
