This project currently uses 4 different data sources (although we should discuss removing some - they were useful for sanity checking parcel tax payments but at the end of the day are duplicative)

These datasets are too big for github but here are locations where they can be retrieved:
• [Parcel_Data_2021_Table.csv](https://data.lacounty.gov/datasets/70d93266f45a4080a97b285a471493cd_0/explore?filters=eyJTaXR1c1N0cmVldCI6WyJIWVBFUklPTiBBVkUiXSwiUm9sbFllYXIiOlsiMjAyNCJdfQ%3D%3D)
• [TTC_Secured_Property_Taxes.csv](https://data.lacounty.gov/datasets/7b8a630eb5ca48ca830fb9487343147e_0/explore)
• [Zoning.geojson.csv](https://geohub.lacity.org/datasets/f2b84d74972a4084aac79fbe504d9b11_15/explore?location=34.051469%2C-118.366046%2C16.23)
• [Parcels.gdb](https://data.lacounty.gov/documents/4d67b154ae614d219c58535659128e71/about)

Suggestion to simplify to just the following:
Zoning.geojson.csv - GIS file of zoning overlays for each area
Parcels.gdb - GIS file of all parcels, we are using this to assign zoning areas and also calculate acres of parcels (this includes parcel improvement and land evaluations for 2024 which we can use instead of TTC_Secured or Parcel_Data)