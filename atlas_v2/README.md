# Readme atlas v2

Version: 2025-04-14

Transfered files:
/work/ik1017/Ingest/C3S-CICA-ATLAS/

## generated manifest

```
ssh rook
```

Run the following find + sed:
```
find /mnt/lustre/work/ik1017/Ingest/C3S-CICA-ATLAS/v02 -type f -name "*.nc" | sed 's|/mnt/lustre/work/ik1017/Ingest/C3S-CICA-ATLAS/v02|https://data.mips.climate.copernicus.eu/thredds/fileServer/esg_c3s-cica-atlas/v02|' > manifest-atlas-v2_20250414.txt
```