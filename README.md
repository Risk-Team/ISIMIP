# Tutorial on automatically downloading and processing ISIMIP3b climate input data
The script folder contains the function that needs to be called from a shell to download and then aggregate (optional) the netCDF files into ncml files. For this last step, it is necessary to have a conda environment with R and climate4R packages installed. 

## How to run the function
Open a terminal, place the isimip.sh script anywhere and run:

```
bash isimip.sh

```
```
Download climate data with specified parameters.

Options:
  -m   model_choices    Specify the model choices: GFDL-ESM4, MPI-ESM1-2-HR, IPSL-CM6A-LR, MRI-ESM2-0, UKESM1-0-LL, all
  -v   variable         Specify one or more variables separated by space: hurs, huss, pr, prsn, ps, tas, tasmax, tasmin. Enclose multiple variables in quotes (e.g tas hurs)
  -s   scenario         Specify the scenario: historical, ssp126, ssp585, all

```
