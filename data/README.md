# Data

This directory contains sample datasets for course exercises and assignments.

## Important Notes

⚠️ **Large data files are excluded from version control** to keep the repository size manageable.

### Accessing Data

Large datasets used in the course are available through:
1. Course-provided cloud storage links
2. Public data repositories (NOAA, NASA, USGS, etc.)
3. Instructions in specific notebooks for downloading data

### Data Structure

```
data/
├── examples/          # Small example datasets (committed to repo)
├── climate/           # Climate and meteorological data (download separately)
├── hydrology/         # Hydrological datasets (download separately)
├── remote_sensing/    # Satellite and remote sensing data (download separately)
└── processed/         # Processed data outputs (generated locally)
```

## Example Datasets

The `examples/` subdirectory contains small sample datasets that are included in the repository for quick testing and learning.

## External Data Sources

### Climate Data
- [NOAA Climate Data Online](https://www.ncdc.noaa.gov/cdo-web/)
- [NASA Earth Data](https://earthdata.nasa.gov/)
- [ECMWF ERA5](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5)

### Hydrological Data
- [USGS Water Data](https://waterdata.usgs.gov/nwis)
- [GRDC Global Runoff Data](https://www.bafg.de/GRDC/)

### Remote Sensing
- [Google Earth Engine](https://earthengine.google.com/)
- [Landsat Data](https://www.usgs.gov/landsat-missions)
- [Sentinel Data](https://sentinels.copernicus.eu/)

## Data Download Scripts

Check the `notebooks/` directory for scripts that automate downloading required datasets for specific exercises.

## Usage Guidelines

- Do not commit large data files (> 10MB) to the repository
- Document data sources and preprocessing steps
- Maintain consistent file naming conventions
- Store processed outputs in `processed/` subdirectory
