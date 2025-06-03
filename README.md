# Time-series-plot

Steps to create a time-series plots

1. Regrid the CMIP6 ETCCDI data from their origion grids into 1x1 degree (aligned with FROG's database grids)

2. Apply a common mask (1 degree resolution, from REGEN-ALL-v2019) to seperate land and sea regions.

3. Extract data from the common domain (50S-50N, 180E-180W) for the period 1980-2014, applying  the mask for data

4. Compute time series of the weighted regionally indices from the masked data and plot based on your purpose. 


