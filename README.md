# 📊 City of LA Parcel Tax × Zoning Analysis

This project analyzes property tax efficiency patterns across zoning categories and proximity to transit in the City of Los Angeles. It combines spatial, zoning, and tax data to support scenario modeling for policy decisions related to rezoning near major transit stops.

## 📁 Data Sources

All data files are available in the project’s [Google Drive folder](https://drive.google.com/drive/u/1/folders/1fJEfDxHA0YpBhul3MBmf373YE_oL0G6y).

| File | Description |
|------|-------------|
| **`Parcels.gdb`** | Geometry data for all individual land parcels in the City of LA. Primarily used to calculate parcel acreage. |
| **`Metro_Stops_SB_79.geojson`** | Geospatial data for areas near transit stops affected by SB79, including defined proximity tiers. |
| **`Parcel tax by zoning - assigned zoning.csv`** | Mapping of zoning categories into simplified zoning buckets to make analysis more transparent and interpretable. *(Prepared by SFA Policy Team)* |
| **`Parcel_Data_2021_Table_-2691831558175163259.csv`** | Property tax data for every parcel in the City of Los Angeles (2024 snapshot). |
| **`ZONING_PLY_20250403.geojson`** | Zoning data for the City of LA. This intentionally uses a older version excluding recent DTLA rezoning for consistency. |
