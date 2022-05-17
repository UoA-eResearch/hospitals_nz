# hospitals_nz
A Python Jupyter notebook to train a model to predict hospital discharges in NZ


## Installation

`pip install -r requirements.txt`

## Running

`jupyter-notebook train.ipynb`

### Data sources

- Hospital Discharges (hospital_discharges folder): https://www.health.govt.nz/nz-health-statistics/health-statistics-and-data-sets/publicly-funded-hospital-discharges-series/publicly-funded-hospital-discharges-series/publicly-funded-hospital-discharges-series
- NZ Public Hospitals (NZ_Public_Hospitals.geojson): https://hub.arcgis.com/datasets/2340b390407642859ee4a43fd20d490f_0/about
- District Health Boards (statsnzdistrict-health-board-2015-FGDB.zip): https://datafinder.stats.govt.nz/layer/87883-district-health-board-2015/
- Territorial Authority Local Board (statsnzterritorial-authority-local-board-2021-clipped-generalised-FGDB.zip): https://datafinder.stats.govt.nz/layer/105136-territorial-authority-local-board-2021-clipped-generalised/
- Subnational Population Projections (subnational-population-projections-2018base-2048.xlsx): https://www.stats.govt.nz/information-releases/subnational-population-projections-2018base2048