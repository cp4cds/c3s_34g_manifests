# Manifest files for CMIP5

## version 2023.02.03

So, I tried to re-generate the CMIP5 manifest files from my C3S-CMIP5 local archive.
I have 174,222 files under C3S-CMIP5.
2,535 files are related to 3hr or fx variables, so I excluded them as you confirmed CDS do not distributed those frequencies. I just excluded them from the manifests, data are still available for the time being.

Then I dispatched the remaining files following the four CDS catalogues entries and produced the following up-to-date manifest files :

- monthly variable on pressure level
https://thredds-su.ipsl.fr/thredds/fileServer/ipsl_thredds/glipsl/manifest_C3S2_380_CMIP5_monthly_pressure_level_20230131.txt

- daily variables on pressure level
https://thredds-su.ipsl.fr/thredds/fileServer/ipsl_thredds/glipsl/manifest_C3S2_380_CMIP5_daily_pressure_level_20230131.txt

- monthly variables on single level
https://thredds-su.ipsl.fr/thredds/fileServer/ipsl_thredds/glipsl/manifest_C3S2_380_CMIP5_monthly_single_level_20230131.txt

- daily variables on single level
https://thredds-su.ipsl.fr/thredds/fileServer/ipsl_thredds/glipsl/manifest_C3S2_380_CMIP5_daily_single_level_20230131.txt

From my point of you, you can safely replace the current CMIP5 manifests by those. They directly reflect what we have on IPSL and DKRZ filesystems so all the files exist and are available for download (we checked with Carsten at the beginning of C3S2_380 we had the same hard copies of CMIP5, CMIP6 and CORDEX archives).


## version 2022.04.22

Copied from this GitHub repo:
https://github.com/cp4cds/c3s-manifiests 

latest update on this repo: 2020.08.17

latest manifest version: 2019.07.24
