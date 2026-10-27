# chimaliro-school-site-accessibility
<<<<<<< HEAD

Suitability mapping for new primary school sites in **TA Chimaliro, Thyolo, Malawi**.

## Ministry of Education criteria
1. ≥ **2 km** from any existing primary school
2. ≤ **500 m** from a main road
3. **Not** in a protected area

## Summary of results
- Final suitable area: **~XX km²** (see notebook)
- Outputs:
  - `outputs/suitable_areas_map.png` — static map
  - `outputs/interactive_map.html` — interactive map

## Data sources
| Dataset | Source | CRS |
|---|---|---|
| TA boundary | Malawi NSO / HDX | EPSG:4326 → 32736 |
| Protected areas | WDPA | EPSG:4326 → 32736 |
| Roads | OpenStreetMap / Geofabrik | EPSG:4326 → 32736 |
| Primary schools | OSM / HDX | EPSG:4326 → 32736 |

## Reproducing
```bash
pip install geopandas shapely fiona pyproj matplotlib folium mapclassify
cd notebooks
jupyter notebook school_site_analysis.ipynb
=======
chimaliro-school-site-accessibility
>>>>>>> 0bbcbd39e8de334fb10640f96d79e78055114ef8
