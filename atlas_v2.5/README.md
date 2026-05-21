# Readme atlas v2.5

Version: 2026-05-20

Transfered files:
/work/ik1017/Ingest/C3S-CICA-ATLAS/

## generated manifest

```
ssh rook
```

Run the following find + sed:
```
find /mnt/lustre/work/ik1017/Ingest/C3S-CICA-ATLAS/v025 -type f -name "*.nc" | sed 's|/mnt/lustre/work/ik1017/Ingest/C3S-CICA-ATLAS/v025|https://data.mips.climate.copernicus.eu/thredds/fileServer/esg_c3s-cica-atlas/v025|' > manifest-atlas-v25_20260520.txt
```