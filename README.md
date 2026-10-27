## Towhidul Islam

I'm a geospatial researcher based in Chittagong, Bangladesh. Most of my work is about
how the ground moves in the cities and hills of the Bengal delta, and how subsidence,
landslides and flooding add up to risk for the people living there. I use radar satellite
data (InSAR), some machine learning, and a fair amount of my own code when the existing
tools don't do what I need.

In 2025 I started SAR.Sense Geointelligence Lab, where I lead three research projects on
ground deformation and hazard risk. I'm now looking for a funded PhD in geohazards,
climate risk or Earth observation, and I'm ready to do it full-time.

You can find more on my [portfolio](https://towhidulislam27.github.io/) and
[LinkedIn](https://www.linkedin.com/in/towhidullslam), or email me at m.towhid92@gmail.com.

### Research projects

| Project | About |
|---|---|
| **[bGMO](https://github.com/TowhidulIslam27/bGMO)**<br>[live map](https://bgmo.sarsense.com) | Bangladesh Ground Motion Observatory. A web map of land movement in Dhaka, Chattogram, Khulna, Barishal, Sylhet and Cumilla, built from Sentinel-1 PS-InSAR results for 2016 to 2024. Click any point to see how it moved over time, or switch to the combined product that separates vertical and east-west motion. Rates are relative to a local reference area for now; calibration against GNSS is the next step. |
| **[xai-urban-subsidence-bd](https://github.com/TowhidulIslam27/xai-urban-subsidence-bd)** | Why is the ground sinking in Dhaka and Chattogram, and do the same drivers apply in both? Explainable machine learning on my PS-InSAR vertical velocities: about 64 terrain, geology, land-cover and urban factors per city on a 100 m grid, screened and modelled with spatial cross-validation. Work in progress. The first results are up, including the baseline a model that only knows coordinates sets for the factors to beat. |
| **Integrated landslide early warning** (private for now) | A daily landslide early warning for the Rangamati hills, the Rohingya camps in Ukhia and Teknaf, and the hills of Chattogram city. So far: an inventory of about 3,400 landslide records and a first terrain-only susceptibility baseline, tested on held-out blocks and compared with simple baselines. Rainfall thresholds and InSAR slope movement come next. |

### Software

| Project | About |
|---|---|
| **BanGIS Pro**<br>[demo on my portfolio](https://towhidulislam27.github.io/) | A desktop GIS ("GIS Made Simple") I've been building since 2024 for SAR and geospatial research. 312 tools in 27 toolboxes so far, Google Earth Engine and open data built in, a Python console, and Hiron, an AI agent that plans and runs a chain of GIS and SAR steps from a plain request. Each tool writes a short report citing the method it uses. A dedicated SAR environment, SAR Studio, is still in development. Not public yet. |
| **[Portfolio](https://github.com/TowhidulIslam27/TowhidulIslam27.github.io)** | The source for my personal site. |

### What I'm working on

- A land deformation map for the whole of Bangladesh from Sentinel-1 (2016 to 2024),
  with six cities processed so far and the rest in progress.
- Explaining where and why the ground moves, using SHAP on models that link InSAR
  deformation to geology and human activity, and testing whether those drivers carry
  over from Dhaka to Chattogram ([repo](https://github.com/TowhidulIslam27/xai-urban-subsidence-bd)).
- Adding rainfall thresholds and InSAR slope movement to the landslide susceptibility
  baseline, to test a daily early warning for 2017 to 2026.

### Background

I did a PgD in Geo-Information Science and Earth Observation at ITC, University of
Twente, where my study tracked a slow-moving landslide with PS-InSAR. Before that I
did an MSc in Urban Management and Development at IHS, Erasmus University Rotterdam
(on how urban flooding disrupts travel in Chittagong), and my BSc and MS in Geography
and Environmental Studies at the University of Chittagong.

Outside the lab I've worked as a GIS consultant for icddr,b, as a junior researcher at
the Red Cross Red Crescent Climate Centre on heat risk in Rajshahi, and I've taught GIS
courses for some years.

### Tools I use most

For SAR and InSAR: SNAP, StaMPS, LiCSBAS, PyGMTSAR and SARscape, mostly with
Sentinel-1 and ALOS-2. For GIS and remote sensing: QGIS, ArcGIS Pro, Google Earth
Engine, ENVI and GRASS. I write most things in Python (NumPy, GeoPandas, Rasterio), with
some R and MATLAB, and use PostGIS for data. For web and desktop tools: React,
TypeScript, FastAPI, Tauri, MapLibre and Leaflet.

### Papers

In preparation, as lead author:

- Islam, T., et al. Ground motion and infrastructure exposure in Bangladesh's three
  largest cities from multi-geometry PS-InSAR.
- Islam, T., et al. Do the drivers of urban subsidence transfer between cities? An
  InSAR-XAI look into Dhaka and Chattogram City of Bangladesh.

Co-authored:

- Uddin, M.S., Mahmud, K., Islam, T., and Rahman, M.A. (2026). Explainable machine
  learning assessment of hydroclimatic and land-surface controls on agricultural
  drought in North-Western Bangladesh. *Journal of Hydrology*, under review.
- Uddin, M.S., Mitra, B., Rahman, M.S., Mahmud, K., Islam, T., Rahman, S.M., and
  Rahman, M.M. (2026). Integrating shared socioeconomic pathways and deep learning for
  future CO2 emission forecasts in major European Union economies. *Environment,
  Development and Sustainability*, minor revision.
- Subedi, A., Islam, T., Khan, R., Hassan, A., and Hoogesteger, S. (2022).
  *Identification of heat threshold and heat hotspots in Rajshahi, Bangladesh.* Red
  Cross Red Crescent Climate Centre.

The full list is on my portfolio. If you work on InSAR, subsidence or landslide risk,
feel free to get in touch.
