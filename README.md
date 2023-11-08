# sdsc-bootcamp-smash-draft

## Agenda for morning checkin

- Mon: brainstorm research questions; choose dataset; draft chapters and distribute individual tasks for first half, including data collection and initial exploration; Model selection if using regression (Victor).
  - Research Question:
    - Accessiblity: Walkshed of metro stations (Janna)
    - House price ~ demography / POI
      - Census: Population / Income / Race / Education / Unemployment (Ushashi)
      - Numbers of Job (Zheng) 
      - POI: school / hosptials / restaurants / parks (Mengyu; overpass turbo)
    - Median house price / HOUSING OCCUPANCY / UNITS ~ metro accessibility / bike accessibility
  - Kind of analysis:
    - Accessibility: walkshed for metro stations; open data dc (demography);
    - GWR/Spatial Error: house price/bike data (after aggregated by census tract); location choice; scale matters
    - Compete destination: key factors
  - Data:
    - Support: census tract for DC (Zheng)
    - Metro station location; ridership, need to double check (Janna);
    - Bike sharing: Capitalbike; aggregation (Zheng)
    - POI dataset: overture map / osm (Zheng)
    - Housing price: ACS Housing Characteristics DC Census Tract (Median price for each census tract)
- Tue: checkpoint for 1st half; draft 2nd half chapter
  - Dataset: restaurant point (~2200 in total); relation to metro station
  - Analysis (Package used):
    - Data preparation for OSM POI (requests/json) See the notebook POIs.ipynb (Mengyu)
    - Buffer/Join/Aggregration (GeoPandas/Pandas) (Mengyu)
    - Numerical calcuation: density (Numpy/Geopandas) (Mengyu)
    - Reprojection to the diff between projected and native mapping (pyproj/Geopandas) (Mengyu)
    
    - Walkshed (OSMnx/networkx/shapely/alphashape?) and interactive mapping [WMATA walkshed](https://www.mwcog.org/newsroom/2019/07/16/walksheds-show-planners-how-easily-people-can-walk-to-transit/) (Janna/Zheng)
    - Food location density by each walkshed. (Spatial operation) (Open practice?)
    - Accessibility to each restaurant by calculating spatial weights of metro / bike share / parking lot
    - NDVI calculation / Green space (Rasterio/rasterstats) (Janna)
    - Hotspot Analysis (PySAL) (Ushashi)
    - Plotting (Folium / leafmap / matplotlib) (Victor)
  - Slides: Outline (Zheng) / Template (Janna)
- Wed: first draft for analysis, ploting, and storytelling
  - Mengyu would lead orchestration of the jupyter notebook.
  - Janna share the walkshed code to Mengyu and calculate NDVI.
  - Ushashi would lead hotspot analysis that refer the [previous code](https://github.com/willgeary/PythonSpatialDataScience/blob/main/notebook.ipynb)
  - Victor would lead plotting / mapping.
  - Zheng will keep working on the slides and backup notebook composing.
- Thu: Rehearsal for time recording
- Fri: RR environment setup and final proofread

## Evening progress report tracker
- Mon:
- Tue:
- Wed:
- Thu:
- Fri:


## Chapters

### 1 Data overview and explorative analysis

### 2 
