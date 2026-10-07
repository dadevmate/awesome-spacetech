# Awesome Space Tech ![Awesome](https://awesome.re/badge.svg)

> A systems-level index of space technology — from orbital mechanics and ground stations to space medicine and in-situ manufacturing. Covers both **open-source tools** and **official agency/data sources**, plus the **commercial space ecosystem**. Organized by **engineering domain**.

**Last Updated: 2026-10-04**

[![Domains](https://img.shields.io/badge/Domains-22-blue?style=for-the-badge)](#-table-of-contents)
[![Tools](https://img.shields.io/badge/Tools-250%2B-green?style=for-the-badge)](#-table-of-contents)
[![Agencies](https://img.shields.io/badge/Agencies-30%2B-red?style=for-the-badge)](#2-space-agencies--institutions)
[![Companies](https://img.shields.io/badge/Companies-150%2B-purple?style=for-the-badge)](#13-private-space-companies--startups)
[![Updated](https://img.shields.io/badge/Updated-2026--10--04-orange?style=for-the-badge)](#)

---

## Table of Contents

1. [Existing Awesome Space Lists](#1-existing-awesome-space-lists)
2. [Space Agencies & Institutions](#2-space-agencies--institutions)
3. [Space Data Platforms & APIs](#3-space-data-platforms--apis)
4. [Satellite View & Real-Time Imagery](#4-satellite-view--real-time-imagery)
5. [Satellite Tracking & SSA](#5-satellite-tracking--space-situational-awareness)
6. [Ground Stations & SDR](#6-ground-stations--sdr)
7. [Space Weather & Heliophysics](#7-space-weather--heliophysics)
8. [Rocket Launch Monitoring](#8-rocket-launch-monitoring)
9. [Mission Design & Astrodynamics](#9-mission-design--astrodynamics)
10. [Space Robotics & Autonomy](#10-space-robotics--autonomy)
11. [Space Medicine & Human Performance](#11-space-medicine--human-performance)
12. [Space Food & Bioregenerative Life Support](#12-space-food--bioregenerative-life-support)
13. [Private Space Companies & Startups](#13-private-space-companies--startups)
14. [Space Capsule Manufacturers](#14-space-capsule-manufacturers)
15. [Private Space Telescopes & Observatories](#15-private-space-telescopes--observatories)
16. [Commercial Space Stations](#16-commercial-space-stations)
17. [In-Space Manufacturing & Assembly](#17-in-space-manufacturing--assembly)
18. [Asteroid Mining & Resource Utilization](#18-asteroid-mining--resource-utilization)
19. [Spacecraft Software & Flight Frameworks](#19-spacecraft-software--flight-frameworks)
20. [Space Law, Policy & Regulation](#20-space-law-policy--regulation)
21. [News, Media & Community](#21-news-media--community)
22. [Reference Architectures](#22-reference-architectures)

---

## 1. Existing Awesome Space Lists

*Start here. These are the established community lists — build on top of them, don't duplicate.*

| List | Maintainer | Focus | Link |
|---|---|---|---|
| **awesome-space** | The Orbital Index | Space code, APIs, data | [orbitalindex/awesome-space](https://github.com/orbitalindex/awesome-space) |
| **Space Systems Engineering Resources** | HaralDev | Mission design, visualisation, courses | [HaralDev/Space-Systems-Engineering-Resources](https://github.com/HaralDev/Space-Systems-Engineering-Resources) |
| **awesome-space-robotics** | AndrejOrsula | Space robotics resources | [AndrejOrsula/awesome-space-robotics](https://github.com/AndrejOrsula/awesome-space-robotics) |
| **awesome-spacehackers** | Space Hackers Club | Aerospace data & code | [spacehackersclub/awesome-spacehackers](https://github.com/spacehackersclub/awesome-spacehackers) |
| **awesome-aerospace-engineering** | Mahran Sayed | Learning resources | [mahran-sayed/awesome-aerospace-engineering](https://github.com/mahran-sayed/awesome-aerospace-engineering) |
| **awesome-spacecraft-engineering-datasets** | Patrick Fleith | Datasets | [patrickfleith/awesome-spacecraft-engineering-datasets](https://github.com/patrickfleith/awesome-spacecraft-engineering-datasets) |
| **foss-space** | Galactic Embassy | FOSS space tech | [galactic-embassy/foss-space](https://github.com/galactic-embassy/foss-space) |
| **awesome-open-source-space-data-apis** | Brandon Himpfen | APIs | [brandonhimpfen/awesome-open-source-space-data-apis](https://github.com/brandonhimpfen/awesome-open-source-space-data-apis) |

> **How this list differs:** The above lists index *projects*. This list indexes **engineering domains** plus **official agency resources** and the **commercial space ecosystem**.

---

## 2. Space Agencies & Institutions

*The primary sources. Every serious space project touches at least one of these.*

### Government Space Agencies

| Agency | Country | Website | Open Data | Notes |
|---|---|---|---|---|
| **NASA** | 🇺🇸 USA | [nasa.gov](https://www.nasa.gov) | [data.nasa.gov](https://data.nasa.gov) · [api.nasa.gov](https://api.nasa.gov) | The reference. Open data, APIs, software catalog. |
| **ISRO** | 🇮🇳 India | [isro.gov.in](https://www.isro.gov.in) | [Bhuvan](https://bhuvan.nrsc.gov.in) · [MOSDAC](https://www.mosdac.gov.in) | Chandrayaan, Mangalyaan, Gaganyaan. |
| **ESA** | 🇪🇺 Europe | [esa.int](https://www.esa.int) | [open.esa.int](https://open.esa.int) | Copernicus, Gaia, Euclid. |
| **JAXA** | 🇯🇵 Japan | [jaxa.jp](https://global.jaxa.jp) | [JAXA Open Data](https://www.jaxa.jp/library/index_e.html) | Hayabusa2, ISS Kibo module. |
| **Roscosmos** | 🇷🇺 Russia | [roscosmos.ru](https://www.roscosmos.ru) | — | Soyuz, Progress, ISS. |
| **CNSA** | 🇨🇳 China | [cnsa.gov.cn](http://www.cnsa.gov.cn) | — | Tiangong, Chang'e lunar program. |
| **CSA** | 🇨🇦 Canada | [asc-csa.gc.ca](https://www.asc-csa.gc.ca) | [open.canada.ca](https://open.canada.ca) | Canadarm, Dextre. |
| **DLR** | 🇩🇪 Germany | [dlr.de](https://www.dlr.de) | [DLR Open Data](https://www.dlr.de/en/research-and-transfer/open-data) | COLUMBUS, TerraSAR-X. |
| **CNES** | 🇫🇷 France | [cnes.fr](https://cnes.fr) | [data.cnes.fr](https://data.cnes.fr) | Ariane, SPOT, Pléiades. |
| **ASI** | 🇮🇹 Italy | [asi.it](https://www.asi.it) | [ASI Open Data](https://www.asi.it/en/science/open-data/) | Vega, COSMO-SkyMed. |
| **UKSA** | 🇬🇧 UK | [gov.uk/ukspaceagency](https://www.gov.uk/government/organisations/uk-space-agency) | [UK Space Data](https://www.gov.uk/government/collections/uk-space-data) | OneWeb, SSTL. |
| **AEB** | 🇧🇷 Brazil | [gov.br/aeb](https://www.gov.br/aeb) | [INPE](https://www.gov.br/inpe) | Alcântara launch center. |
| **KARI** | 🇰🇷 South Korea | [kari.re.kr](https://www.kari.re.kr/eng) | — | Nuri, Danuri lunar orbiter. |
| **UAE Space Agency** | 🇦🇪 UAE | [space.gov.ae](https://space.gov.ae) | — | Hope Mars mission, Rashid rover. |
| **Israel Space Agency** | 🇮🇱 Israel | [gov.il/isa](https://www.gov.il/en/departments/israel_space_agency) | — | Beresheet lunar lander. |
| **CONAE** | 🇦🇷 Argentina | [argentina.gob.ar/conae](https://www.argentina.gob.ar/ciencia/conae) | — | SAOCOM satellites. |
| **SSAU** | 🇺🇦 Ukraine | [nkau.gov.ua](https://www.nkau.gov.ua) | — | Zenit, Cyclone launch vehicles. |

### Multinational & Intergovernmental

| Organization | Website | Notes |
|---|---|---|
| **UNOOSA** | [unoosa.org](https://www.unoosa.org) | UN Office for Outer Space Affairs. |
| **COPUOS** | [unoosa.org/copuos](https://www.unoosa.org/oosa/en/ourwork/copuos/index.html) | Committee on Peaceful Uses of Outer Space. |
| **ITU** | [itu.int](https://www.itu.int) | Spectrum coordination. |
| **IADC** | [iadc-home.org](https://www.iadc-home.org) | Inter-Agency Space Debris Coordination. |
| **CGMS** | [cgms-info.org](https://www.cgms-info.org) | Coordination Group for Meteorological Satellites. |
| **CEOS** | [ceos.org](https://ceos.org) | Committee on Earth Observation Satellites. |
| **GEO** | [earthobservations.org](https://www.earthobservations.org) | Group on Earth Observations. |
| **EUSPA** | [euspa.europa.eu](https://www.euspa.europa.eu) | EU Agency for the Space Programme. |

### Research Institutions

| Institution | Country | Website | Notes |
|---|---|---|---|
| **JPL** | 🇺🇸 USA | [jpl.nasa.gov](https://www.jpl.nasa.gov) | NASA's premier robotic exploration lab. |
| **APL** | 🇺🇸 USA | [jhuapl.edu](https://www.jhuapl.edu) | Johns Hopkins Applied Physics Lab. New Horizons, Parker Solar Probe. |
| **SwRI** | 🇺🇸 USA | [swri.org](https://www.swri.org) | Southwest Research Institute. |
| **NASA CCMC** | 🇺🇸 USA | [ccmc.gsfc.nasa.gov](https://ccmc.gsfc.nasa.gov) | Community Coordinated Modeling Center. Space weather models. |
| **NASA GSFC** | 🇺🇸 USA | [gsfc.nasa.gov](https://www.nasa.gov/goddard) | Goddard Space Flight Center. |
| **NASA JSC** | 🇺🇸 USA | [jsc.nasa.gov](https://www.nasa.gov/johnson) | Johnson Space Center. Human spaceflight. |
| **NASA KSC** | 🇺🇸 USA | [ksc.nasa.gov](https://www.nasa.gov/kennedy) | Kennedy Space Center. Launch operations. |
| **ISRO Satellite Centre** | 🇮🇳 India | [isac.gov.in](https://www.isac.gov.in) | Satellite design and integration. |
| **ISRO Propulsion Complex** | 🇮🇳 India | [iprc.gov.in](https://www.iprc.gov.in) | Liquid propulsion systems. |
| **Vikram Sarabhai Space Centre** | 🇮🇳 India | [vssc.gov.in](https://www.vssc.gov.in) | Launch vehicle development. |
| **ESA ESTEC** | 🇪🇺 Europe | [esa.int/ESTEC](https://www.esa.int/About_Us/ESTEC) | European Space Research and Technology Centre. |
| **ESA ESOC** | 🇪🇺 Europe | [esa.int/ESOC](https://www.esa.int/About_Us/ESOC) | European Space Operations Centre. |
| **DLR GSOC** | 🇩🇪 Germany | [dlr.de/gsoc](https://www.dlr.de/en/gsoc) | German Space Operations Center. |
| **Aerospace Corporation** | 🇺🇸 USA | [aerospace.org](https://aerospace.org) | Federally funded R&D center. CAVE Lab for autonomous systems. |

---

## 3. Space Data Platforms & APIs

*Where the data lives. Official sources and open platforms.*

### Open Data Portals

| Platform | Provider | URL | Data Types |
|---|---|---|---|
| **NASA Open Data** | NASA | [data.nasa.gov](https://data.nasa.gov) | All NASA datasets |
| **NASA APIs** | NASA | [api.nasa.gov](https://api.nasa.gov) | APOD, Mars Rover, EPIC, NeoWs |
| **ESA Open Data** | ESA | [open.esa.int](https://open.esa.int) | Earth observation, science |
| **Copernicus** | ESA/EU | [copernicus.eu](https://www.copernicus.eu) | Sentinel satellite data |
| **Copernicus Data Space Ecosystem** | ESA/EU | [dataspace.copernicus.eu](https://dataspace.copernicus.eu) | Cloud-native processing, APIs (Sentinel Hub, openEO, STAC, OGC) |
| **Earthdata** | NASA | [earthdata.nasa.gov](https://earthdata.nasa.gov) | Earth science data |
| **USGS EarthExplorer** | USGS | [earthexplorer.usgs.gov](https://earthexplorer.usgs.gov) | Landsat, terrain |
| **NOAA NCEI** | NOAA | [ncei.noaa.gov](https://www.ncei.noaa.gov) | Climate, ocean, geophysical |
| **ISRO Bhuvan** | ISRO | [bhuvan.nrsc.gov.in](https://bhuvan.nrsc.gov.in) | Indian Earth observation |
| **MOSDAC** | ISRO | [mosdac.gov.in](https://www.mosdac.gov.in) | Meteorological & oceanographic |
| **JAXA G-Portal** | JAXA | [gportal.jaxa.jp](https://gportal.jaxa.jp) | Earth observation |
| **DLR Open Data** | DLR | [dlr.de/en/research-and-transfer/open-data](https://www.dlr.de/en/research-and-transfer/open-data) | German space data |
| **CNES Data** | CNES | [data.cnes.fr](https://data.cnes.fr) | French space data |

### APIs & Catalogs

| API | Provider | URL | Notes |
|---|---|---|---|
| **NASA API Portal** | NASA | [api.nasa.gov](https://api.nasa.gov) | APOD, Mars, EPIC, NeoWs |
| **Space-Track** | USSF | [space-track.org](https://www.space-track.org) | Full satellite catalog |
| **CELESTRAK** | Public | [celestrak.org](https://celestrak.org) | TLE data |
| **Launch Library 2** | The Space Devs | [thespacedevs.com/llapi](https://thespacedevs.com/llapi) | Launch data |
| **N2YO** | N2YO | [n2yo.com/api](https://www.n2yo.com/api/) | Satellite tracking |
| **Heavens-Above** | Public | [heavens-above.com](https://heavens-above.com) | Pass predictions |
| **JPL Horizons** | NASA JPL | [ssd.jpl.nasa.gov/horizons](https://ssd.jpl.nasa.gov/horizons) | Ephemeris |
| **NASA SPICE** | NASA NAIF | [naif.jpl.nasa.gov/naif](https://naif.jpl.nasa.gov/naif) | Observation geometry |
| **NASA OSDR** | NASA | [osdr.nasa.gov](https://osdr.nasa.gov) | Open Science Data Repository |
| **NASA Exoplanet Archive** | NASA | [exoplanetarchive.ipac.caltech.edu](https://exoplanetarchive.ipac.caltech.edu) | Exoplanet data |
| **SIMBAD** | CDS | [simbad.u-strasbg.fr](https://simbad.u-strasbg.fr) | Astronomical objects |
| **VizieR** | CDS | [vizier.u-strasbg.fr](https://vizier.u-strasbg.fr) | Astronomical catalogs |
| **ADS** | Harvard | [ui.adsabs.harvard.edu](https://ui.adsabs.harvard.edu) | Astrophysics papers |
| **arXiv astro-ph** | arXiv | [arxiv.org/list/astro-ph](https://arxiv.org/list/astro-ph/recent) | Preprints |
| **CCMC DONKI** | NASA | [ccmc.gsfc.nasa.gov](https://ccmc.gsfc.nasa.gov) | Space Weather Database Of Notifications, Knowledge, Information |

### Multi-Provider Fetch Tools

| Tool | Type | Link | Notes |
|---|---|---|---|
| **PyGeoFetch** | Library/CLI | [PyPI](https://pypi.org/project/pygeofetch/) | Universal satellite data pipeline — unified access to 22+ repositories (NASA, ESA, JAXA, USGS, Planet, Maxar, etc.) with one CLI or Python API. YAML pipeline orchestration, adaptive parallel downloads, STAC output, Docker, cron scheduler. |

---

## 4. Satellite View & Real-Time Imagery

*Live and near-real-time satellite imagery platforms. View the Earth as it looks right now.*

### Global Satellite Viewers

| Platform | Provider | URL | Latency | Notes |
|---|---|---|---|---|
| **NASA Worldview** | NASA | [worldview.earthdata.nasa.gov](https://worldview.earthdata.nasa.gov) | 3–4 hours | Interactive browsing of 1,000+ global satellite imagery layers. Full-resolution, daily imagery. Wildfire, hurricane, iceberg tracking. |
| **Worldview Snapshots** | NASA | [wvs.earthdata.nasa.gov](https://wvs.earthdata.nasa.gov) | Near real-time | Low-bandwidth, lightweight tool for image snapshots in various formats. |
| **GIBS** | NASA | [earthdata.nasa.gov/gibs](https://earthdata.nasa.gov/gibs) | 3–5 hours | Standardized web services (WMTS, TWMS, WMS, GDAL) providing fast access to 1,000+ global visualizations. |
| **NOAA Earth in Real-Time** | NOAA | [nnvl.noaa.gov](https://www.nnvl.noaa.gov) | Near real-time | Interactive global weather and environmental imagery. |
| **Zoom Earth** | Public | [zoom.earth](https://zoom.earth) | Daily updates | International cloud imagery updated daily from NASA satellites. |
| **Sentinel Hub EO Browser** | ESA | [apps.sentinel-hub.com/eo-browser](https://apps.sentinel-hub.com/eo-browser/) | Near real-time | Browse Copernicus Sentinel imagery. Free and commercial tiers. |
| **Sentinel Playground** | Sinergise | [apps.sentinel-hub.com/sentinel-playground](https://apps.sentinel-hub.com/sentinel-playground/) | Near real-time | Quick access to Sentinel-2 imagery. |
| **Copernicus Open Access Hub** | ESA | [scihub.copernicus.eu](https://scihub.copernicus.eu/dhus/#/home) | Near real-time | Full Sentinel data archive. |
| **Google Earth** | Google | [earth.google.com](https://earth.google.com) | Varies | High-resolution imagery from Landsat-8 and aerial sources. |
| **Google Maps Satellite View** | Google | [google.com/maps](https://www.google.com/maps) | Varies | The most accessible satellite view. |
| **Bing Maps** | Microsoft | [bing.com/maps](https://www.bing.com/maps) | Varies | Aerial and satellite imagery. |
| **Esri World Imagery** | Esri | [esri.com](https://www.esri.com/en-us/arcgis/products/arcgis-online) | Varies | High-resolution global imagery. |
| **Mapbox Satellite** | Mapbox | [mapbox.com/maps/satellite](https://www.mapbox.com/maps/satellite) | Varies | Customizable satellite basemaps. |
| **Satellites Pro** | Public | [satellites.pro](https://satellites.pro/) | Near real-time | Satellite map viewer. |
| **TerraServer** | Public | [terraserver.com](https://www.terraserver.com) | Varies | Aerial and satellite imagery. |
| **Landsat Explorer** | USGS/NASA | [landsat.arcgis.com](https://landsat.arcgis.com) | Varies | Landsat imagery viewer. |
| **Planet Explorer** | Planet Labs | [planet.com/explorer](https://www.planet.com/explorer/) | Daily | Daily satellite imagery. |
| **Maxar SecureWatch** | Maxar | [maxar.com/securewatch](https://www.maxar.com/securewatch) | Varies | High-resolution commercial imagery. |
| **OneAtlas** | Airbus | [oneatlas.airbus.com](https://oneatlas.airbus.com) | Varies | Pleiades and SPOT imagery. |
| **EOS LandViewer** | EOS Data Analytics | [eos.com/landviewer](https://eos.com/landviewer/) | Varies | Satellite imagery analysis. |

### Real-Time Tracking & Live Maps

| Platform | URL | Notes |
|---|---|---|
| **SatelliteTracker3D** | [satellitetracker3d.com](https://satellitetracker3d.com/) | Real-time 3D satellite and debris visualization. |
| **LeoLabs Platform** | [platform.leolabs.space](https://platform.leolabs.space/visualization) | Commercial SSA visualization. |
| **N2YO** | [n2yo.com](https://www.n2yo.com) | Real-time satellite tracking. |
| **Heavens-Above** | [heavens-above.com](https://heavens-above.com) | Pass predictions. |
| **What's Overhead** | [martianalpha.com/overhead](https://martianalpha.com/overhead) | Live ISS, Tiangong and Starlink-train tracker with pass predictions for your location. |
| **Celestia** | [celestia.space](https://celestia.space) | Free, open-source 3D space simulation. |
| **Stellarium Web** | [stellarium-web.org](https://stellarium-web.org) | Browser planetarium. |

### Mobile Apps

| App | Platform | Notes |
|---|---|---|
| **Mappa: GPS & Live Earth Camera** | iOS | Live satellite & Earth view. |
| **Live Satellite View - 3D Map** | iOS | Real-time insight into traffic, weather. |
| **3D Earth Map & HD Live Camera** | Android | Real-time camera streaming worldwide. |

---

## 5. Satellite Tracking & Space Situational Awareness

*Orbit determination, conjunction analysis, debris tracking, and space traffic management.*

### Tracking & Visualization (Open Source)

| Tool | Type | Language | Link | Notes |
|---|---|---|---|---|
| **KeepTrack** | Web app | TypeScript | [thkruz/keeptrack.space](https://github.com/thkruz/keeptrack.space) | 3D visualization of 50,000+ satellites. Simulates 2.5M debris objects at 60fps. Runs offline. |
| **Gpredict** | Desktop | C | [csete/gpredict](https://github.com/csete/gpredict) | Real-time satellite tracking and orbit prediction. The classic. |
| **Look4Sat** | Android | Kotlin | [rt-bishop/Look4Sat](https://github.com/rt-bishop/Look4Sat) | Open-source satellite tracker and pass predictor for Android, inspired by Gpredict. |
| **OrbTrack** | Android | — | [calsurferpunk/Orbtrack](https://github.com/calsurferpunk/Orbtrack) | Track satellites, rocket bodies, debris, planets. |
| **satvis** | Web | JavaScript | [Flowm/satvis](https://github.com/Flowm/satvis) | Satellite orbit visualization and pass prediction with Cesium.js. |
| **PyPredict** | Library | Python | [spel-uchile/Pypredict](https://github.com/spel-uchile/Pypredict) | Real-time satellite tracker and orbit propagator. |
| **satellite-tracker** | Library | JavaScript | [dsuarezv/satellite-tracker](https://github.com/dsuarezv/satellite-tracker) | 3D satellite tracker library with up-to-date data from CELESTRAK. |

### SSA & Orbit Determination

| Tool | Type | Language | Link | Notes |
|---|---|---|---|---|
| **SSAPy** | Library | Python | [LLNL/SSAPy](https://github.com/LLNL/SSAPy) | Fast, flexible orbit modeling and analysis for LEO to cislunar. Vectorized for HPC. |
| **Tudat** | Library | C++/Python | [tudat-team/tudat](https://github.com/tudat-team/tudat) | TU Delft Astrodynamics Toolbox. High-fidelity orbit estimation for planetary science and SSA. |
| **ASTRA-Core** | Library | Python | [ISHANTARE/ASTRA](https://github.com/ISHANTARE/ASTRA) | Autonomous Space Traffic Risk Analyzer. Rigorous Python astrodynamics engine. |
| **MOCAT-pySSEM** | Library | Python | [IBM/MOCAT](https://github.com/IBM/MOCAT) | MIT Orbital Capacity Assessment Tools. Space environment modeling for debris. |
| **rotastellar-intel** | Library | Python/JS | [PyPI](https://pypi.org/project/rotastellar-intel/) | TLE parsing, SGP4 propagation, conjunction analysis. |

### Space Debris

| Tool | Type | Link | Notes |
|---|---|---|---|
| **Orbital Sentinel AI** | Platform | [MneTheDev/Orbit_Sentinel_AI](https://github.com/MneTheDev/Orbit_Sentinel_AI) | NASA-inspired AI for debris tracking, collision prediction, orbital safety. |
| **Space Trash Map** | Web | [Antonov-Artem/space-trash-map](https://github.com/Antonov-Artem/space-trash-map) | Interactive platform to track, analyze, and visualize space debris. |
| **ESA Space Debris** | Data | [esa.int/Space_Safety/Space_Debris](https://www.esa.int/Space_Safety/Space_Debris) | Official ESA debris office. |
| **NASA Orbital Debris** | Data | [orbitaldebris.jsc.nasa.gov](https://orbitaldebris.jsc.nasa.gov) | NASA ODPO. |
| **EU SST** | Service | [eusst.eu](https://www.eusst.eu/) | EU Space Surveillance and Tracking. Collision avoidance, re-entry analysis. |

### Commercial SSA Providers

| Provider | URL | Notes |
|---|---|---|
| **LeoLabs** | [leolabs.space](https://leolabs.space) | Radar-based LEO tracking. |
| **Slingshot Aerospace** | [slingshot.space](https://slingshot.space) | AI-powered SSA solutions. |
| **ExoAnalytic Solutions** | [exoanalytic.com](https://exoanalytic.com) | Telescope network for SSA. |
| **Kratos Space** | [kratosspace.com](https://www.kratosspace.com) | OpenSpace SSA platform. |
| **GMV** | [gmv.com](https://www.gmv.com) | European SSA market. |
| **ThothX Meridian** | [thothx.com](https://thothx.com) | Real-time radar monitoring of GEO. |

---

## 6. Ground Stations & SDR

*Software-defined radio, telemetry decoding, and ground station orchestration.*

### Ground Station Orchestration

| Tool | Type | Link | Notes |
|---|---|---|---|
| **Ground Station** | Web app | [sgoudelis/ground-station](https://github.com/sgoudelis/ground-station) | Full-featured SDR orchestration platform. Satellite passes, SDR waterfall, GMSK telemetry decoding, multiple SDR devices, antenna rotators. AI speech-to-text for amateur voice. |
| **SatDump** | Desktop | [satdump/satdump](https://github.com/satdump/satdump) | Signal processing and decoding for weather satellites, ham radio, and more. |
| **ground-station-core** | Library | [skypodolsky/ground-station-core](https://github.com/skypodolsky/ground-station-core) | All-in-one utility for SDR-based satellite tracking. |
| **CygnusRFI** | Tool | [0xCoto/CygnusRFI](https://github.com/0xCoto/CygnusRFI) | RFI analysis for ground stations. |
| **CardSat** | Hardware | [prstoetzer/CardSat](https://github.com/prstoetzer/CardSat) | Open-source amateur satellite ground station controller on M5Stack Cardputer ADV (ESP32-S3, credit-card-sized). |

### Community Ground Station Networks

| Network | URL | Notes |
|---|---|---|
| **SatNOGS** | [satnogs.org](https://satnogs.org) | Global network of open ground stations. |
| **TinyGS** | [tinygs.com](https://tinygs.com) | LoRa satellite ground station network. |
| **NASA DSN Now** | [eyes.nasa.gov/dsn](https://eyes.nasa.gov/dsn/dsn.html) | Live Deep Space Network status. |
| **AMSAT** | [amsat.org](https://www.amsat.org) | Amateur radio satellite org. |

### SDR & Signal Processing

| Tool | Type | Link | Notes |
|---|---|---|---|
| **GNU Radio** | Framework | [gnuradio/gnuradio](https://github.com/gnuradio/gnuradio) | The standard SDR framework. |
| **RTL-SDR** | Library | [osmocom/rtl-sdr](https://github.com/osmocom/rtl-sdr) | Drivers for RTL2832U-based SDRs. |
| **SDRangel** | Desktop | [f4exb/sdrangel](https://github.com/f4exb/sdrangel) | TX/RX SDR and signal analyzer. |
| **inspectrum** | Desktop | [miek/inspectrum](https://github.com/miek/inspectrum) | Offline radio signal analyzer. |
| **SDR#** | Desktop | [airspy.com/download](https://airspy.com/download/) | Popular Windows SDR software. |

### Ground Segment Software

| Tool | Type | Link | Notes |
|---|---|---|---|
| **ORQOS** | Platform | [ESA](https://resilience.esa.int/archives/projects/orqos) | ESA Telecom Ground Segment. Integrated NOC and MCS for constellation-scale operations. Beam/link assignment, traffic engineering. |
| **Yamcs** | Framework | [yamcs.org](https://yamcs.org) | Open-source mission control framework. Also Yamcs Cloud. |
| **Astral** | Platform | [Starion](https://www.stariongroup.eu) | Flexible, component-based ground segment solution. High automation. |
| **CelesHub** | Platform | [Groundspace](https://www.groundspace.fr) | Cloud-native ground segment software. Scales horizontally. |
| **GALAXY** | System | [NASA](https://www.nasa.gov) | Real-time command and telemetry system. |
| **Major Tom** | Platform | [Xplore](https://xplore.com) | Scalable, cloud-based mission control software. |

---

## 7. Space Weather & Heliophysics

*Ionospheric modeling, radiation belts, solar activity, and geomagnetic storms.*

### Official Space Weather Services

| Service | Provider | URL | Notes |
|---|---|---|---|
| **NOAA SWPC** | NOAA | [swpc.noaa.gov](https://www.swpc.noaa.gov) | US Space Weather Prediction Center. |
| **ESA SWE** | ESA | [swe.ssa.esa.int](https://swe.ssa.esa.int) | ESA Space Weather Service Network. |
| **NASA CCMC** | NASA | [ccmc.gsfc.nasa.gov](https://ccmc.gsfc.nasa.gov) | Community Coordinated Modeling Center. |
| **CCMC ISWA** | NASA | [iswa.ccmc.gsfc.nasa.gov](https://iswa.ccmc.gsfc.nasa.gov) | Integrated Space Weather Analysis system. |
| **SpaceWeather.com** | Public | [spaceweather.com](https://spaceweather.com) | Daily space weather news. |
| **SOHO** | NASA/ESA | [sohowww.nascom.nasa.gov](https://sohowww.nascom.nasa.gov) | Solar and Heliospheric Observatory. |
| **SDO** | NASA | [sdo.gsfc.nasa.gov](https://sdo.gsfc.nasa.gov) | Solar Dynamics Observatory. |
| **Parker Solar Probe** | NASA | [parkersolarprobe.jhuapl.edu](https://parkersolarprobe.jhuapl.edu) | Mission site. |
| **Solar Orbiter** | ESA/NASA | [esa.int/Solar_Orbiter](https://www.esa.int/Science_Exploration/Space_Science/Solar_Orbiter) | Mission site. |
| **SPDF Heliophysics** | NASA | [spdf.gsfc.nasa.gov/heliophysics_resources.html](https://spdf.gsfc.nasa.gov/heliophysics_resources.html) | Directory of data repositories and archives worldwide. |
| **Canadian Space Science Data Portal** | CSA | [spaceweather.gc.ca](https://www.spaceweather.gc.ca) | Space science analytic tools and data. |
| **AuroraX** | Canada | [aurorax.space](https://aurorax.space/) | Auroral data and tools for researchers and citizen scientists. |

### Modeling & Analysis

| Tool | Type | Link | Notes |
|---|---|---|---|
| **Kamodo** | Library | [nasa/Kamodo](https://github.com/nasa/Kamodo) | NASA CCMC's open-source tool for access, interpolation, and visualization of space weather models. |
| **MAGE** | Model | [NASA-CGS/MAGE](https://github.com/NASA-CGS/MAGE) | NASA Center for Geospace Storms' predictive space weather model. |
| **PINNBARDS** | Tool | [NSF NCAR/SwRI](https://news.ucar.edu/133059) | PINN-Based Active Regions Distribution Simulator. Bridges surface observations and deep solar magnetic dynamics. |
| **HELIOSICA** | Framework | [Zenodo](https://zenodo.org) | Nine-parameter solar MHD framework for real-time prediction of geomagnetic storm intensity. |
| **SpacePy** | Library | [spacepy/spacepy](https://github.com/spacepy/spacepy) | Community-driven space science library. |
| **SunPy** | Library | [sunpy/sunpy](https://github.com/sunpy/sunpy) | Solar physics data analysis. |
| **PyHC** | Community | [heliopython.org](https://heliopython.org) | Python in Heliophysics Community. |
| **SciQLop** | IDE | [atst.osups.universite-paris-saclay.fr](https://atst.osups.universite-paris-saclay.fr) | IDE for space physics. Browse, visualise, script, annotate, share. |

### Radiation & Particle Data

| Source | Provider | URL | Notes |
|---|---|---|---|
| **OSDR** | NASA | [osdr.nasa.gov](https://osdr.nasa.gov) | Open Science Data Repository. |
| **ERFNet** | ESA/ASI | [erfnet.space](https://erfnet.space) | ESA/ASI space radiation research. |
| **H-SPAR DB** | Intl. | [bioinformatics.cing.ac.cy/H-SPARDB](https://bioinformatics.cing.ac.cy/H-SPARDB/) | Human spaceflight omics for space health. |
| **OMNI** | NASA | [omniweb.gsfc.nasa.gov](https://omniweb.gsfc.nasa.gov) | Hourly near-Earth solar wind magnetic field, plasma, energetic proton flux data. |

---

## 8. Rocket Launch Monitoring

*Live tracking, telemetry, notifications, and historical data.*

### Open Source Tools

| Tool | Type | Link | Notes |
|---|---|---|---|
| **Earth to Orbit Monitoring** | Dashboard | [crow50/earth-to-orbit-monitoring](https://github.com/crow50/earth-to-orbit-monitoring) | Real-time launch updates. Fetches from Launch Library 2, filters Cape Canaveral, stores in PostgreSQL. |
| **rocket.watch** | Web app | [yasiupl/rocket.watch](https://github.com/yasiupl/rocket.watch) | Comprehensive platform for all space launches, landings, suborbital events. |
| **RocketScope** | Simulator | [Jgoodall13/RocketScope](https://github.com/Jgoodall13/RocketScope) | Rocket launch tracker and simulator. Simulates dynamics, visualizes telemetry, implements abort protocols. |
| **RocketTraker** | Hardware | [AstronomyLiveYt/RocketTraker](https://github.com/AstronomyLiveYt/RocketTraker) | Track launches with off-the-shelf telescope hardware. Trajectory predictions from flightclub.io. |
| **Zenith** | Dashboard | [kohld/zenith](https://github.com/kohld/zenith) | AI-powered space intelligence. LEO satellites, deep-space probes, aurora forecasts, global launches. |
| **SpaceX-API** | API | [r-spacex/SpaceX-API](https://github.com/r-spacex/SpaceX-API) | REST API for SpaceX launch, rocket, core, capsule, Starlink, launchpad, landing pad data. |
| **spacex-go** | CLI | [jesusrp98/spacex-go](https://github.com/jesusrp98/spacex-go) | Simple, powerful open-source SpaceX launch tracker. |
| **expo-router-rocket-launch-tracker** | Mobile | [EvanBacon/expo-router-rocket-launch-tracker](https://github.com/EvanBacon/expo-router-rocket-launch-tracker) | Rocket launch tracker built with Expo Router and React Server Components. |

### Websites & Live Trackers

| Site | URL | Notes |
|---|---|---|
| **Space Launch Schedule** | [spacelaunchschedule.com](https://spacelaunchschedule.com) | Upcoming launches. |
| **Next Spaceflight** | [nextspaceflight.com](https://nextspaceflight.com) | Launch schedule + live. |
| **Spaceflight Now** | [spaceflightnow.com](https://spaceflightnow.com) | Launch coverage. |
| **NASASpaceflight** | [nasaspaceflight.com](https://www.nasaspaceflight.com) | Live coverage + forum. |
| **Everyday Astronaut** | [everydayastronaut.com](https://everydayastronaut.com) | Launch guides. |
| **SpaceX Now** | [spacexnow.com](https://spacexnow.com) | Launch alerts. |
| **ISRO Launch Schedule** | [isro.gov.in/launchers](https://www.isro.gov.in/launchers.html) | Official ISRO launches. |

### APIs

| API | URL | Notes |
|---|---|---|
| **Launch Library 2** | [thespacedevs.com/llapi](https://thespacedevs.com/llapi) | The standard launch API. |
| **SpaceX-API** | [api.spacexdata.com](https://api.spacexdata.com) | SpaceX data. |
| **RocketLaunch.Live** | [rocketlaunch.live/api](https://www.rocketlaunch.live/api) | Launch API. |

---

## 9. Mission Design & Astrodynamics

*Trajectory optimization, orbit propagation, and mission architecture.*

### Mission Design Tools

| Tool | Type | Link | Notes |
|---|---|---|---|
| **GMAT** | Desktop | [gmat.gsfc.nasa.gov](https://gmat.gsfc.nasa.gov) | NASA's General Mission Analysis Tool. Enterprise, multi-mission, open-source. |
| **PyKEP** | Library | [esa/pykep](https://github.com/esa/pykep) | ESA's scientific library for interplanetary trajectory design. |
| **hohmannpy** | Library | [hohmannpy/hohmannpy](https://github.com/hohmannpy/hohmannpy) | Rapid spacecraft design and iteration. |
| **smd** | Library | [ChristopherRabotin/smd](https://github.com/ChristopherRabotin/smd) | Space Mission Design. SPICE-enhanced continuous thrust interplanetary propagator. |
| **satmad** | Library | [egemenimre/satmad](https://github.com/egemenimre/satmad) | Satellite mission analysis and design. |
| **orbitSim3D** | Simulator | [arda-guler/orbitSim3D](https://github.com/arda-guler/orbitSim3D) | Sophisticated astrodynamics and space mission simulator. N-body trajectories. |
| **RocketLab** | Library | [quantumnic/rocketlab](https://github.com/quantumnic/rocketlab) | Rocket trajectory simulator and aerospace toolkit. Rust. |
| **AstraX** | Simulator | [arshc0der/AstraX](https://github.com/arshc0der/AstraX) | Pro solar system architect. Enterprise-grade simulator with real physics. |
| **SATMO** | Tool | [AIAA](https://arc.aiaa.org/doi/10.2514/6.2026-2269) | Open-source, MATLAB-based, six-node thermal analysis program for CubeSats. |
| **OpenSat Mission Lab** | Platform | [Samuelson777/OpenSat-Mission-Lab-Versions](https://github.com/Samuelson777/OpenSat-Mission-Lab-Versions) | Open-source CubeSat mission digital twin and secure operations lab. |
| **OpenSOAP** | Tool | [smallsateurope.com](https://smallsateurope.com) | Open-source, systems-level mission planning and analysis tool. |
| **DEMODOS** | Framework | [UniversalScientificTechnologies/DEMODOS](https://github.com/UniversalScientificTechnologies/DEMODOS) | Mission design and simulation. |

### Orbit Propagation

| Tool | Language | Link | Notes |
|---|---|---|---|
| **Skyfield** | Python | [skyfielders/python-skyfield](https://github.com/skyfielders/python-skyfield) | High-precision astronomy. |
| **poliastro** | Python | [poliastro/poliastro](https://github.com/poliastro/poliastro) | Astrodynamics and orbital mechanics. |
| **Orekit** | Java | [CS-SI/Orekit](https://github.com/CS-SI/Orekit) | Flight dynamics. |
| **SPICE** | Toolkit | [naif.jpl.nasa.gov/naif](https://naif.jpl.nasa.gov/naif) | NASA's observation geometry system. |
| **JPL Horizons** | Web/API | [ssd.jpl.nasa.gov/horizons](https://ssd.jpl.nasa.gov/horizons) | Ephemeris service. |

### CubeSat & SmallSat Resources

| Tool | Type | Link | Notes |
|---|---|---|---|
| **Basilisk** | Framework | [CU Boulder](https://hanspeterschaub.info/basilisk/) | Open-source astrodynamics simulation framework. Python scripting. |
| **Nyx** | Library | [nyxspace.com](https://nyxspace.com) | Open-source astrodynamics library in Rust. |
| **OpenSat-Mission-Lab** | Platform | [GitHub](https://github.com/Samuelson777/OpenSat-Mission-Lab-Versions) | Digital twin for CubeSat missions. |

---

## 10. Space Robotics & Autonomy

*Rovers, manipulators, free-flyers, and autonomous systems.*

### Frameworks & Middleware

| Tool | Type | Link | Notes |
|---|---|---|---|
| **Space ROS** | Framework | [space-ros/space-ros](https://github.com/space-ros/space-ros) | NASA, Open Robotics, Blue Origin. Open-source spacecraft flight software framework for robotic applications. Fork of ROS 2. |
| **RACS2 Bridge** | Bridge | [JAXA/RACS2](https://github.com/JAXA/RACS2) | ROS2 and cFS system bridge. Demonstrated on Int-Ball2 on ISS. |
| **PX4Space** | Framework | [DISCOMER/PX4-Space-Systems](https://github.com/DISCOMER/PX4-Space-Systems) | Adaptation of the PX4 software stack for spacecraft analogs and space robotics facilities. |
| **ESROCOS** | Framework | [H2020](https://www.researchportal.be) | Open-source framework for space robotics software. Model-based engineering. |
| **mjorbit** | Simulator | [arXiv](https://arxiv.org) | Simulation framework for space robotics built on MuJoCo. |
| **PLEXIL** | Language | [NASA](https://www.nasa.gov) | Plan representation and execution language for reliable automation of spacecraft and robotic operations. |

### Hardware Platforms

| Platform | Type | Link | Notes |
|---|---|---|---|
| **CADRE** | Rovers | [JPL](https://www.jpl.nasa.gov/missions/cadre) | Cooperative Autonomous Distributed Robotic Exploration. Team of shoebox-sized rovers to the Moon. |
| **Curiosity** | Rover | [NASA](https://science.nasa.gov/mission/msl-curiosity/) | Car-sized Mars rover powered by RTG. |
| **Perseverance** | Rover | [NASA](https://science.nasa.gov/mission/mars-2020-perseverance/) | Mars rover landed in Jezero Crater 2021. |
| **ExoMy** | Rover | [ESA](https://esa-prl.github.io/ExoMy) | Open source build-it-yourself rover developed by ESA. |
| **JPL Open Source Rover** | Rover | [jplopensourcerover.com](https://jplopensourcerover.com) | Open source build-it-yourself rover developed by JPL. |
| **Lunar Rover Mini (LRM)** | Rover | [DLR-RY/Lunar-Rover-Mini](https://github.com/DLR-RY/Lunar-Rover-Mini) | Modular open-source rover for space robotics research. |
| **Ingenuity** | Helicopter | [NASA](https://en.wikipedia.org/wiki/Ingenuity_(helicopter)) | 1.8 kg coaxial-rotor helicopter. First powered, controlled flight on another planet. |
| **Dragonfly** | Rotorcraft | [NASA](https://science.nasa.gov/mission/dragonfly/) | Dual-quadcopter rotorcraft designed to fly on Saturn's moon Titan. |
| **RoboSimian** | Robot | [JPL](https://www-robotics.jpl.nasa.gov/how-we-do-it/systems/robosimian) | Four-limbed robot with seven degrees of freedom per limb. |
| **Int-Ball2** | Free-flyer | [JAXA](https://github.com/JAXA/Int-Ball2) | ISS internal camera robot. ROS middleware, Gazebo simulation. |
| **MASCOT** | Lander | [DLR/CNES](https://en.wikipedia.org/wiki/Mobile_Asteroid_Surface_Scout) | Mobile Asteroid Surface Scout. |
| **RASSOR** | Robot | [NASA KSC](https://technology.nasa.gov/patent/KSC-TOPS-7) | Regolith Advanced Surface Systems Operations Robot. |

### Research Labs

| Lab | Institution | Focus |
|---|---|---|
| **LASER** | USC | Laboratory for Autonomous Systems and Exploration Robotics. |
| **CAVE Lab** | Aerospace Corporation | Collaborative and Autonomous Vehicle Ecosystem. On-orbit refueling. |
| **Orbital Robotics Lab (ORL)** | ESA ESTEC | Europe's largest two-dimensional free-floating testbed. |
| **Naval Center for Space Technology** | NRL | Space robotics rendezvous and proximity operations. |

---

## 11. Space Medicine & Human Performance

*Physiological modeling, medical risk assessment, and astronaut health.*

### Official Resources

| Source | Provider | URL | Notes |
|---|---|---|---|
| **NASA HRP** | NASA | [humanresearchroadmap.nasa.gov](https://humanresearchroadmap.nasa.gov) | Human Research Program. |
| **NASA LSDA** | NASA | [lsda.jsc.nasa.gov](https://lsda.jsc.nasa.gov) | Life Sciences Data Archive. Active archive from 1961 (Mercury) through current flight and analog studies. |
| **NASA Life Sciences Portal** | NASA | [catalog-beta.data.gov](https://catalog-beta.data.gov) | Data platform for accessing LSDA. |
| **ESA Space Medicine** | ESA | [esa.int](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration) | European space medicine. |
| **ISRO Human Spaceflight** | ISRO | [isro.gov.in/Gaganyaan](https://www.isro.gov.in/Gaganyaan.html) | Gaganyaan program. |
| **OSDR** | NASA | [osdr.nasa.gov](https://osdr.nasa.gov) | Open Science Data Repository. Multiomics, physiological, telemetry, radiation data. |
| **H-SPAR DB** | Intl. | [bioinformatics.cing.ac.cy/H-SPARDB](https://bioinformatics.cing.ac.cy/H-SPARDB/) | Human spaceflight platform for analysis and research. |
| **SOMA** | Cornell | [soma.weill.cornell.edu](https://soma.weill.cornell.edu/) | Space Omics and Medical Atlas. Integrated data and sample repository. |
| **ERFNet** | ESA/ASI | [erfnet.space](https://erfnet.space) | Space radiation research. |
| **TRISH** | NASA | [nasa.gov](https://www.nasa.gov) | Translational Research Institute for Space Health. |

### Research Centers & Institutions

| Center | Institution | Focus |
|---|---|---|
| **Space Health Center** | Cleveland Clinic | Understanding and mitigating effects of spaceflight on human health. |
| **Trivedi Institute for Space and Global Biomedicine** | University of Pittsburgh | Translational space research. Founding director: Kate Rubins. |
| **Center for Space Medicine Research** | Cedars-Sinai | Microgravity effects on heart function, stem cell biology. |
| **Space Medicine** | UCF College of Medicine | Research, clinical, education efforts for keeping space travelers healthy. |
| **ISRO-AIIMS Collaboration** | ISRO/AIIMS | Memorandum of Understanding for Cooperation in Space Medicine and Research. |

### Tools & Calculators

| Tool | Type | Link | Notes |
|---|---|---|---|
| **Aerospace Medicine Calculators** | Library | [Zenodo](https://zenodo.org/records/19955917) | ~150 pure functions across 28 modules. Atmospheric physiology, thermal stress, decompression, fatigue, G-tolerance, cosmic radiation dose. React dashboard, FastAPI wrapper. |
| **Selectron** | Engine | [Zenodo](https://zenodo.org/records/) | Bayesian multi-criteria scoring for analog-astronaut selection. |
| **CMO-DA** | AI Assistant | [Red Hat case study](https://www.redhat.com) | NASA testing RamaLama to support an AI medical assistant for deep space missions. |

---

## 12. Space Food & Bioregenerative Life Support

*Closed-loop food production, diet optimization, and life support systems.*

### Official Programs & Research

| Program | Provider | URL | Notes |
|---|---|---|---|
| **NASA Space Food Systems** | NASA | [nasa.gov/space-food](https://www.nasa.gov/space-food-systems) | Space food systems lab. |
| **MELiSSA** | ESA | [melissafoundation.org](https://www.melissafoundation.org) | Micro-Ecological Life Support System Alternative. Closed-loop food production. |
| **HOBI-WAN** | ESA | [esa.int](https://www.esa.int) | Hydrogen Oxidizing Bacteria In Weightlessness As a source of Nutrition. Testing protein production in microgravity aboard ISS. |
| **EDEN LUNA** | DLR | [DLR](https://elib.dlr.de) | Semi-closed, compact space food production. Bio-regenerative autonomous life support, AI-assisted robotics. |
| **ISRO Space Food** | ISRO | [isro.gov.in](https://www.isro.gov.in) | Indian space food research. |
| **JAXA Space Food** | JAXA | [jaxa.jp](https://global.jaxa.jp) | Japanese space food. |

### Tools & Databases

| Tool | Type | Link | Notes |
|---|---|---|---|
| **GENOMARS** | Pipeline | [GabrieleEllena/GENOMARS](https://github.com/GabrieleEllena/GENOMARS) | Diet optimization models and genomic screening for space food. |
| **SpaceLID** | Database | [bidd.group/spacelid](https://bidd.group/spacelid/) | Space Life Research Database. Food intake, storage, usage, menus. 236 entries. |
| **Epicurious** | Project | [spaceapps-epicurious/spacefood](https://github.com/spaceapps-epicurious/spacefood) | Food component storage and point-of-consumption production for long-duration flight. |
| **Food Fabricator** | Project | [danielng01/Food-Fabricator](https://github.com/danielng01/Food-Fabricator) | Warm Earthlike meals for deep-space crews. |

### Research Directions

| Topic | Notes |
|---|---|
| **Precision Nutrition** | Multi-omics and digital twins enable real-time, personalized space nutrition. AI-driven feedback systems. |
| **Food Biomanufacturing** | Microbial, plant, and cellular manufacturing platforms for in-situ food production. |
| **3D/4D Food Printing** | Programmable, sensory-rich astronaut meals. |
| **Closed-Loop Ecosystems** | Coupling energy and material flows among astronauts, photosynthetic and heterotrophic bioreactors. |

---

## 13. Private Space Companies & Startups

*The commercial space ecosystem. Launch providers, satellite operators, and infrastructure companies.*

### Launch Providers

| Company | Country | Website | Vehicle(s) | Notes |
|---|---|---|---|---|
| **SpaceX** | 🇺🇸 USA | [spacex.com](https://www.spacex.com) | Falcon 9, Falcon Heavy, Starship | Reusable rockets. Starlink constellation. Crew Dragon. |
| **Blue Origin** | 🇺🇸 USA | [blueorigin.com](https://www.blueorigin.com) | New Shepard, New Glenn | Suborbital tourism, orbital launch. Orbital Reef station. |
| **Rocket Lab** | 🇺🇸/🇳🇿 | [rocketlabusa.com](https://www.rocketlabusa.com) | Electron, Neutron | Small launch leader. Photon satellite bus. |
| **Relativity Space** | 🇺🇸 USA | [relativityspace.com](https://www.relativityspace.com) | Terran R | 3D-printed rockets. |
| **Firefly Aerospace** | 🇺🇸 USA | [firefly.com](https://firefly.com) | Alpha, Eclipse | Small-to-medium launch. |
| **Stoke Space** | 🇺🇸 USA | [stokespace.com](https://www.stokespace.com) | Nova | Fully reusable second stage. |
| **United Launch Alliance** | 🇺🇸 USA | [ulalaunch.com](https://www.ulalaunch.com) | Vulcan Centaur | Boeing-Lockheed joint venture. |
| **Arianespace** | 🇪🇺 Europe | [arianespace.com](https://www.arianespace.com) | Ariane 6, Vega | European launch provider. |
| **Isar Aerospace** | 🇩🇪 Germany | [isaraerospace.com](https://www.isaraerospace.com) | Spectrum | European private launch. |
| **PLD Space** | 🇪🇸 Spain | [pldspace.com](https://www.pldspace.com) | Miura 1, Miura 5 | European private launch. |
| **Rocket Factory Augsburg (RFA)** | 🇩🇪 Germany | [rfa.space](https://www.rfa.space) | RFA One | European private launch. |
| **Skyroot Aerospace** | 🇮🇳 India | [skyroot.in](https://www.skyroot.in) | Vikram series | First Indian private rocket to reach orbit. |
| **Agnikul Cosmos** | 🇮🇳 India | [agnikul.in](https://agnikul.in) | Agnibaan | 3D-printed rocket engines. |
| **iSpace** | 🇯🇵 Japan | [ispace-inc.com](https://ispace-inc.com) | HAKUTO-R | Lunar lander. |
| **Interstellar Technologies** | 🇯🇵 Japan | [istellartech.com](https://www.istellartech.com/en) | ZERO, MOMO | Japanese private launch. |
| **Space One** | 🇯🇵 Japan | [space-one.co.jp](https://www.space-one.co.jp) | KAIROS | Japanese private launch. |

### Indian Private Space Startups

| Company | Focus | Website | Notes |
|---|---|---|---|
| **Agnikul Cosmos** | Launch vehicles | [agnikul.in](https://agnikul.in) | 3D-printed rocket engines. |
| **Skyroot Aerospace** | Launch vehicles | [skyroot.in](https://www.skyroot.in) | Vikram series. First Indian private orbital launch. |
| **Pixxel Space** | Earth observation | [pixxel.space](https://www.pixxel.space) | Hyperspectral imaging. |
| **Dhruva Space** | Small satellites | [dhruvaspace.com](https://www.dhruvaspace.com) | Satellite platforms and ground stations. |
| **Bellatrix Aerospace** | Propulsion | [bellatrixaerospace.com](https://www.bellatrixaerospace.com) | Electric and chemical propulsion. |
| **GalaxEye Space** | Earth observation | [galaxeye.space](https://www.galaxeye.space) | SAR + optical imaging. |
| **Digantara Research** | SSA | [digantara.com](https://www.digantara.com) | Space debris tracking. |
| **Manastu Space** | Propulsion | [manastuspace.com](https://www.manastuspace.com) | Green propulsion systems. |
| **OrbitAID Aerospace** | Servicing | [orbitaid.space](https://www.orbitaid.space) | Docking mechanisms. |
| **PierSight Space** | SAR | [piersight.space](https://www.piersight.space) | Maritime domain awareness. |
| **TakeMe2Space** | Space infrastructure | [takeme2space.com](https://www.takeme2space.com) | In-orbit compute. |
| **Hex20Labs** | Ground segment | [hex20labs.com](https://www.hex20labs.com) | Ground station services. |

> Source: IN-SPACe / Department of Space, Government of India. ~440 space technology startups registered in India as of 2026.

### Global Space Companies (NASA Partner Directory)

| Company | Website | Focus |
|---|---|---|
| **AAC Clyde Space** | [aac-clydespace.com](https://www.aac-clydespace.com) | Small satellites, CubeSats. |
| **Aerospacelab** | [aerospacelab.com](https://www.aerospacelab.com) | Small satellite manufacturing. |
| **Airbus US Space & Defense** | [airbusus.com](https://www.airbusus.com) | Large-scale space systems. |
| **Alba Orbital** | [albaorbital.com](https://www.albaorbital.com) | PocketQube satellites. |
| **Alén Space** | [alen.space](https://alen.space) | Small satellite platforms. |
| **Apex** | [apexspace.com](https://www.apexspace.com) | Satellite buses. |
| **Argotec** | [argotecgroup.com](https://www.argotecgroup.com) | Space systems, small satellites. |
| **Astranis** | [astranis.com](https://www.astranis.com) | Small geostationary satellites. |
| **Astro Digital** | [astrodigital.com](https://www.astrodigital.com) | Earth observation satellites. |
| **Astroscale** | [astroscale-us.com](https://www.astroscale-us.com) | Debris removal, satellite servicing. |
| **Axelspace** | [axelspace.com](https://www.axelspace.com) | Earth observation smallsats. |
| **BAE Systems** | [baesystems.com](https://www.baesystems.com) | Space electronics, systems. |
| **Berlin Space Technologies** | [berlin-space-tech.com](https://www.berlin-space-tech.com) | Small satellite systems. |
| **BlackSky** | [blacksky.com](https://www.blacksky.com) | Real-time geospatial intelligence. |
| **Blue Canyon Technologies** | [bluecanyontech.com](https://www.bluecanyontech.com) | Small satellite components. |
| **CesiumAstro** | [cesiumastro.com](https://www.cesiumastro.com) | Active phased array communications. |
| **D-Orbit** | [dorbit.space](https://www.dorbit.space) | In-orbit transportation, decommissioning. |
| **Dynetics** | [dynetics.com](https://www.dynetics.com) | Space systems, SLS booster. |
| **Exolaunch** | [exolaunch.com](https://www.exolaunch.com) | Launch integration services. |
| **GomSpace** | [gomspace.com](https://www.gomspace.com) | Nanosatellites, CubeSats. |
| **Iceye** | [iceye.com](https://www.iceye.com) | SAR microsatellites. |
| **In-Space Missions** | [in-space.co.uk](https://www.in-space.co.uk) | Small satellite missions. |
| **ISISPACE** | [isispace.nl](https://www.isispace.nl) | CubeSat systems. |
| **Kleos Space** | [kleos.space](https://www.kleos.space) | RF reconnaissance. |
| **KSAT** | [ksat.no](https://www.ksat.no) | Ground station network. |
| **LeoStella** | [leostella.com](https://www.leostella.com) | Small satellite manufacturing. |
| **Maxar** | [maxar.com](https://www.maxar.com) | Earth intelligence, robotics. |
| **MDA Space** | [mda.space](https://mda.space) | Robotics, satellite systems. |
| **NanoAvionics** | [nanoavionics.com](https://nanoavionics.com) | Small satellite buses. |
| **OHB** | [ohb.de](https://www.ohb.de) | Space systems, satellites. |
| **Planet Labs** | [planet.com](https://www.planet.com) | Earth observation constellation. |
| **Redwire** | [redwirespace.com](https://redwirespace.com) | Space manufacturing, ISS experiments. |
| **Sierra Space** | [sierraspace.com](https://www.sierraspace.com) | Dream Chaser, space stations. |
| **Spire Global** | [spire.com](https://spire.com) | Weather, maritime, aviation data. |
| **SSTL** | [sstl.co.uk](https://www.sstl.co.uk) | Small satellite manufacturing. |
| **Thales Alenia Space** | [thalesaleniaspace.com](https://www.thalesaleniaspace.com) | Large space systems. |
| **Turion Space** | [turionspace.com](https://turionspace.com) | In-space monitoring. |
| **York Space Systems** | [yorkspacesystems.com](https://www.yorkspacesystems.com) | Small satellite platforms. |
| **Voyager Space** | [voyagerspace.com](https://voyagerspace.com) | Space infrastructure, Starlab. |
| **Urban Sky** | [urbansky.com](https://www.urbansky.com) | Stratospheric balloons. |

### Commercial SSA Providers

| Provider | URL | Notes |
|---|---|---|
| **LeoLabs** | [leolabs.space](https://leolabs.space) | Radar-based LEO tracking. |
| **Slingshot Aerospace** | [slingshot.space](https://slingshot.space) | AI-powered SSA solutions. |
| **Maxar Intelligence** | [maxar.com](https://www.maxar.com) | Earth intelligence and SSA data. |
| **Turion Space** | [turionspace.com](https://turionspace.com) | In-space monitoring. |
| **GMV** | [gmv.com](https://www.gmv.com) | European SSA and ground segment. |

---

## 14. Space Capsule Manufacturers

*Companies building crew and cargo capsules for re-entry and downmass.*

### Crew & Cargo Capsules

| Company | Capsule | Website | Status | Notes |
|---|---|---|---|---|
| **SpaceX** | Crew Dragon, Cargo Dragon | [spacex.com](https://www.spacex.com) | Operational | Human and cargo transport to ISS. Reusable. |
| **Boeing** | CST-100 Starliner | [boeing.com](https://www.boeing.com) | Development/Operational | NASA Commercial Crew partner. |
| **Sierra Nevada Corporation** | Dream Chaser | [sierraspace.com](https://www.sierraspace.com) | Development | Lifting-body spaceplane. Cargo and crew variants. |
| **Northrop Grumman** | Cygnus | [northropgrumman.com](https://www.northropgrumman.com) | Operational | Cargo resupply to ISS. |
| **Lockheed Martin** | Orion (with NASA) | [lockheedmartin.com](https://www.lockheedmartin.com) | Development | Deep space crew vehicle. |
| **Blue Origin** | New Shepard capsule | [blueorigin.com](https://www.blueorigin.com) | Operational | Suborbital crew capsule. |
| **Virgin Galactic** | SpaceShipTwo/Delta | [virgingalactic.com](https://www.virgingalactic.com) | Operational | Suborbital spaceplane. |
| **Vast Space** | Haven-1 | [vastspace.com](https://www.vastspace.com) | Development | Commercial space station module. |
| **Axiom Space** | AxEMU, Axiom Station | [axiomspace.com](https://www.axiomspace.com) | Development | Space station modules, spacesuits. |
| **ATMOS Space Cargo** | Phoenix | [atmos-space-cargo.com](https://www.atmos-space-cargo.com) | Development | Re-entry capsules for cargo return. |
| **Outlier Space** | Reusable capsules | [ventureradar.com](https://www.ventureradar.com) | Development | Reusable Earth-return capsules. |
| **Varda Space Industries** | Winnebago | [varda.com](https://varda.com) | Operational | Pharmaceutical manufacturing capsules. |
| **Space Forge** | ForgeStar | [spaceforge.co.uk](https://www.spaceforge.co.uk) | Development | Reusable manufacturing capsules. |
| **Impulse Space** | Orbital maneuvering vehicles | [impulsespace.com](https://www.impulsespace.com) | Development | Last-mile satellite delivery. |
| **Exos Aerospace** | SARGE | [exosaero.com](https://www.exosaero.com) | Development | Suborbital reusable launch vehicle. |
| **World View** | Stratospheric balloon capsules | [worldview.space](https://www.worldview.space) | Development | Stratospheric tourism. |
| **Space Perspective** | Spaceship Neptune | [spaceperspective.com](https://spaceperspective.com) | Paused/Shuttered | Balloon-based tourism. |

### Re-Entry & Downmass Providers

| Company | Service | Website | Notes |
|---|---|---|---|
| **A-SpaX** | Cargo return | [factoriesinspace.com](https://www.factoriesinspace.com/a-spax.html) | Affordable Space Access. |
| **Anduril Industries** | Cargo transport | [anduril.com](https://www.anduril.com) | Defense technology. Space capsule concept. |
| **BlackStar Orbital Technologies** | SpaceDrone | — | Cargo transport. |
| **AZSpace (Ziwei Technology)** | B300, DEAR-3, DEAR-5, C2000 | [azspace.com](https://www.azspace.com) | Cargo transport, re-entry. |
| **Interstellar** | CYZ1 | — | Human spaceflight capsule. |
| **AVIC Chengdu** | HaoLong | — | Chinese cargo capsule. |

---

## 15. Private Space Telescopes & Observatories

*Privately funded space telescopes and observatories. A new frontier in astronomy.*

### Private Space Telescopes

| Telescope | Organization | Website | Status | Notes |
|---|---|---|---|---|
| **Lazuli Space Observatory** | Schmidt Sciences | [schmidtsciences.org](https://www.schmidtsciences.org) | Development | First full-scale privately funded space telescope. Primary mirror larger than Hubble. Wide-field camera, integral-field spectrograph, coronagraph. Deep-space orbit. SSTL developing spacecraft platform. |
| **Habitable Worlds Observatory (HWO)** | NASA (with private partners) | [nasa.gov](https://www.nasa.gov) | Development | "Alien life hunter" telescope. Contracts awarded to Astroscale, BAE Systems, Busek, L3Harris, Lockheed Martin, Northrop Grumman, and Zecoat. |
| **Nancy Grace Roman Space Telescope** | NASA | [nasa.gov](https://www.nasa.gov) | Development | Wide-field infrared survey telescope. Formerly WFIRST. |
| **SPHEREx** | NASA | [nasa.gov](https://www.nasa.gov) | Development | Spectro-Photometer for the History of the Universe. All-sky spectral survey. |

### Private Ground-Based Observatories

| Observatory | Organization | Website | Notes |
|---|---|---|---|
| **Eric and Wendy Schmidt Observatory System** | Schmidt Sciences | [schmidtsciences.org](https://www.schmidtsciences.org) | Three ground-based instruments and one space telescope (Lazuli). Rapid development, open data access. |
| **Las Cumbres Observatory** | LCO | [lco.global](https://lco.global) | Global network of robotic telescopes. |
| **Cerro Tololo Inter-American Observatory** | NOIRLab | [noirlab.edu](https://noirlab.edu) | Ground-based observatory. |
| **W. M. Keck Observatory** | Caltech/UC | [keckobservatory.org](https://keckobservatory.org) | Twin 10-meter telescopes. |
| **Subaru Telescope** | NAOJ | [naoj.org](https://www.naoj.org) | 8.2-meter optical-infrared telescope. |

### Private Satellite Constellations

| Constellation | Company | Website | Notes |
|---|---|---|---|
| **Starlink** | SpaceX | [starlink.com](https://www.starlink.com) | Broadband internet constellation. |
| **OneWeb** | Eutelsat | [oneweb.net](https://oneweb.net) | Broadband internet constellation. |
| **Kuiper** | Amazon | [amazon.com](https://www.amazon.com) | Broadband internet constellation. |
| **Planet Labs** | Planet | [planet.com](https://www.planet.com) | Earth observation constellation. |
| **Iceye** | ICEYE | [iceye.com](https://www.iceye.com) | SAR microsatellite constellation. |
| **Spire Global** | Spire | [spire.com](https://spire.com) | Weather, maritime, aviation data. |
| **Capella Space** | Capella | [capellaspace.com](https://www.capellaspace.com) | SAR Earth observation. |
| **HawkEye 360** | HawkEye 360 | [he360.com](https://www.he360.com) | RF geolocation. |
| **Astrocast** | Astrocast | [astrocast.com](https://www.astrocast.com) | IoT nanosatellite constellation. |
| **Kepler Communications** | Kepler | [kepler.space](https://kepler.space) | In-space connectivity. |

---

## 16. Commercial Space Stations

*Private orbital outposts. The successor to the ISS.*

| Station | Company | Website | Status | Notes |
|---|---|---|---|---|
| **Haven-1** | Vast Space | [vastspace.com](https://www.vastspace.com) | Launching early 2027 | First commercial space station. Bus-size habitat for crews of 4. SpaceX Falcon 9 launch. |
| **Axiom Station** | Axiom Space | [axiomspace.com](https://www.axiomspace.com) | Launching 2028 | Five modules. Designed like a boutique hotel. |
| **Starlab** | Voyager Space | [starlab.com](https://www.starlab.com) | Launching 2028 | International team. NASA-funded. |
| **Orbital Reef** | Blue Origin | [orbitalreef.com](https://www.orbitalreef.com) | Launching 2030 | Joint venture with Sierra Space, Redwire, Boeing. |
| **Orbital Technologies** | Orbital Technologies | — | Concept | Russian commercial station. |
| **Bigelow Aerospace** | Bigelow | [bigelowaerospace.com](https://bigelowaerospace.com) | Dormant | Expandable habitat modules. |
| **Orion Span** | Orion Span | — | Concept | Aurora Station. |

---

## 17. In-Space Manufacturing & Assembly

*ISAM, orbital assembly, digital twins, and autonomous construction.*

### Tools & Projects

| Tool | Type | Link | Notes |
|---|---|---|---|
| **COSMIC-Roadmap** | Tool | [ed-VST/COSMIC-Roadmap](https://github.com/ed-VST/COSMIC-Roadmap) | Generate roadmaps for self-sustained ISAM ecosystems. |
| **tpt-shipyard** | Engine | [tpt-solutions/tpt-shipyard](https://github.com/tpt-solutions/tpt-shipyard) | Computational engine for vehicle construction: sea shipyards, orbital assembly, in-space manufacturing, digital twins. Rust. |
| **NeXosim** | Platform | [asynchronics.com](https://www.asynchronics.com) | Open-source digital-twin platform for rapid spacecraft design and testing. |
| **Interchangeable Tools for Modular In-Orbit Assembly** | Research | [Zenodo](https://zenodo-rdm.web.cern.ch/records/17590203) | Multi-Purpose Tools mounted on robotic arms. Three Tool Sockets attached via SIROM. |
| **IDRA** | Research | [IEEE](https://ieeexplore.ieee.org) | Modular inflatable robotic arm for ISAM. High packing ratio, large operational workspace. |
| **Laser Beam Welding** | Research | [NASA NTRS](https://ntrs.nasa.gov) | Space-rated robotic arm equipped with laser weld head, wire feeder, cameras for in-space welding. |

### Companies & Programs

| Company/Program | Type | Link | Notes |
|---|---|---|---|
| **ArcSpace** | Company | [ESA BSGN](https://bsgn.esa.int) | Sustainable on-orbit joining and cutting solution based on Electron Beam technology. First-of-its-kind in-orbit welding demonstration. |
| **Starflight Dynamics / Levion Materials** | Company | [ESA BSGN](https://bsgn.esa.int) | Zero-gravity growth of next-gen semiconductor materials. Defect-reduced crystals (CZT, InP). |
| **Flawless Photonics** | Company | [ESA BSGN](https://bsgn.esa.int) | Scaling ZBLAN fiber manufacturing from ISS success. Produced nearly 12 km of high-quality ZBLAN optical fibre on ISS. |
| **Varda Space** | Company | [varda.com](https://varda.com) | In-space manufacturing of pharmaceuticals. Flown five Winnebago spacecraft to orbit. $1.6B valuation. |
| **Space Forge** | Company | [spaceforge.co.uk](https://www.spaceforge.co.uk) | ForgeStar vehicle. Low-cost, reusable space vehicle for scalable manufacturing in orbit. |
| **Redwire** | Company | [redwirespace.com](https://redwirespace.com) | Commercial manufacturing in space. Acquired Made In Space in 2020. |
| **NASA ISM** | Program | [nasa.gov/ism](https://www.nasa.gov/in-space-manufacturing) | In-Space Manufacturing program. |
| **ESA ISAM** | Program | [esa.int/ISAM](https://www.esa.int/Enabling_Support/Space_Transportation/In-Space_Manufacturing_and_Assembly) | In-Space Manufacturing & Assembly. |
| **NASA OSAM** | Program | [nasa.gov/osam](https://www.nasa.gov/osam) | On-orbit Servicing, Assembly, Manufacturing. |
| **DARPA RSGS** | Program | [darpa.mil/RSGS](https://www.darpa.mil/program/robotic-servicing-of-geosynchronous-satellites) | Robotic Servicing of Geosynchronous Satellites. |

---

## 18. Asteroid Mining & Resource Utilization

*Companies and technologies for extracting resources from asteroids and planetary bodies.*

### Asteroid Mining Companies

| Company | Country | Website | Focus | Notes |
|---|---|---|---|---|
| **AstroForge** | 🇺🇸 USA | [astroforge.io](https://www.astroforge.io) | Platinum-group metals | DeepSpace-2 mission planned for Q4 2026. Odin spacecraft launched Feb 2025. |
| **TransAstra** | 🇺🇸 USA | [transastra.com](https://www.transastra.com) | Capture bags, asteroid resources | Successfully tested Capture Bag technology aboard ISS Oct 2025. |
| **Planetary Resources** | 🇺🇸 USA | — | Asteroid mining | Historic company (now defunct). |
| **Deep Space Industries** | 🇺🇸 USA | — | Asteroid mining | Historic company (acquired). |
| **Asteroid Mining Corporation** | 🇬🇧 UK | [asteroidminingcorporation.co.uk](https://www.asteroidminingcorporation.co.uk) | Asteroid resources | UK-based. |
| **Origin Space** | 🇨🇳 China | — | Asteroid mining | Chinese asteroid mining company. |
| **Karman+** | 🇺🇸 USA | [karmanplus.com](https://www.karmanplus.com) | Asteroid mining | California-based. |
| **Shackleton Energy Company** | 🇺🇸 USA | — | Lunar and asteroid resources | |
| **Kepler Energy and Space Engineering** | — | — | Space resources | |
| **Celestial Mining** | — | — | Asteroid mining | |
| **Space Resources Inc.** | — | — | Space resources | |
| **Asteroid Initiatives LLC** | — | — | Asteroid mining | |
| **Moon Express** | 🇺🇸 USA | [moonexpress.com](https://www.moonexpress.com) | Lunar resources | |
| **iSpace** | 🇯🇵 Japan | [ispace-inc.com](https://ispace-inc.com) | Lunar resources | |

### ISRU Technologies

| Technology | Organization | Notes |
|---|---|---|
| **Regolith Processing** | NASA KSC | RASSOR robot for regolith excavation. |
| **Oxygen Extraction** | ESA | MOXIE on Perseverance. |
| **Water Extraction** | NASA | Lunar ice prospecting. |
| **Metal Extraction** | Various | Molten regolith electrolysis. |
| **3D Printing with Regolith** | Various | Construction materials from lunar soil. |

---

## 19. Spacecraft Software & Flight Frameworks

*Flight software, command and data handling, and onboard autonomy.*

| Framework | Type | Link | Notes |
|---|---|---|---|
| **cFS** | Flight Software | [nasa/cFS](https://github.com/nasa/cFS) | NASA Core Flight System. The standard for smallsat flight software. |
| **F´** | Flight Software | [nasa/fprime](https://github.com/nasa/fprime) | NASA JPL flight software framework. Component-based. |
| **Space ROS** | Framework | [space-ros/space-ros](https://github.com/space-ros/space-ros) | Space robotics. Fork of ROS 2 hardened for space. |
| **Open MCT** | Mission Control | [nasa/openmct](https://github.com/nasa/openmct) | Web-based mission control framework. |
| **Yamcs** | Mission Control | [yamcs/yamcs](https://github.com/yamcs/yamcs) | Mission control framework for spacecraft. |
| **COSMOS** | Mission Control | [BallAerospace/COSMOS](https://github.com/BallAerospace/COSMOS) | Ball Aerospace's command and control system. |
| **OpenSpace** | Visualization | [OpenSpace/OpenSpace](https://github.com/OpenSpace/OpenSpace) | Astrovisualization project. |
| **ANISE** | Library | [ANISE](https://github.com) | Navigation, Instrument, Spacecraft, and Ephemeris data. |

---

## 20. Space Law, Policy & Regulation

*Treaties, national legislation, and regulatory frameworks.*

| Resource | Provider | URL | Notes |
|---|---|---|---|
| **UNOOSA ASTRO** | UN | [astro.unoosa.org](https://astro.unoosa.org) | Accessing Space Treaty Resources Online. Collection of international and national instruments on space activities. Instruments Database, National Space Law and Policy Database. |
| **UNOOSA** | UN | [unoosa.org](https://www.unoosa.org) | UN Office for Outer Space Affairs. |
| **COPUOS** | UN | [unoosa.org/copuos](https://www.unoosa.org/oosa/en/ourwork/copuos/index.html) | Committee on Peaceful Uses of Outer Space. |
| **ITU** | UN | [itu.int](https://www.itu.int) | Spectrum coordination. |
| **IADC** | Intl. | [iadc-home.org](https://www.iadc-home.org) | Inter-Agency Space Debris Coordination. |
| **HeinOnline Air and Space Law** | Commercial | [heinonline.org](https://heinonline.org) | Collection of books, documents, and scholarly commentary. |
| **ESALEX** | ESA | [esa.int](https://www.esa.int) | ESA Legal Database. |
| **Space Security Portal** | NGO | [spacesecurityportal.org](https://spacesecurityportal.org) | Resources on space security. |
| **Max Planck Encyclopedia of International Law** | Academic | [opil.ouplaw.com](https://opil.ouplaw.com) | Peer-reviewed articles on international public and procedural law. |

---

## 21. News, Media & Community

*Where to follow the industry.*

### News Sites

| Site | URL | Notes |
|---|---|---|
| **SpaceNews** | [spacenews.com](https://spacenews.com) | Industry standard. |
| **NASASpaceflight** | [nasaspaceflight.com](https://www.nasaspaceflight.com) | Live + forum. |
| **Space.com** | [space.com](https://www.space.com) | General space news. |
| **Ars Technica Space** | [arstechnica.com/science/space](https://arstechnica.com/science/space) | Deep technical coverage. |
| **The Orbital Index** | [orbitalindex.com](https://orbitalindex.com) | Weekly newsletter. |
| **SpaceRef** | [spaceref.com](https://spaceref.com) | News aggregation. |
| **Universe Today** | [universetoday.com](https://www.universetoday.com) | Space exploration news. |
| **Phys.org Space** | [phys.org/space-news](https://phys.org/space-news) | Science news. |
| **Payload** | [payloadspace.com](https://payloadspace.com) | Space business. |
| **SpaceWatch.Global** | [spacewatch.global](https://spacewatch.global) | Policy + industry. |

### Community & Forums

| Community | URL | Notes |
|---|---|---|
| **r/space** | [reddit.com/r/space](https://www.reddit.com/r/space) | General space. |
| **r/spacex** | [reddit.com/r/spacex](https://www.reddit.com/r/spacex) | SpaceX community. |
| **r/ISRO** | [reddit.com/r/ISRO](https://www.reddit.com/r/ISRO) | ISRO community. |
| **NASASpaceflight Forum** | [forum.nasaspaceflight.com](https://forum.nasaspaceflight.com) | Technical discussions. |
| **SpaceHackers Club** | [spacehackersclub.com](https://spacehackersclub.com) | Slack community. |
| **The Space Devs** | [thespacedevs.com](https://thespacedevs.com) | Discord + APIs. |

### Podcasts

| Podcast | URL | Notes |
|---|---|---|
| **The Orbital Index** | [orbitalindex.com](https://orbitalindex.com) | Weekly. |
| **Main Engine Cut Off** | [mainenginecutoff.com](https://mainenginecutoff.com) | Industry analysis. |
| **Off-Nominal** | [offnom.com](https://offnom.com) | Engineering + industry. |
| **We Martians** | [wemartians.com](https://www.wemartians.com) | Mars exploration. |
| **The Space Above Us** | [thespaceabove.us](https://thespaceabove.us) | Human spaceflight history. |

---

## 22. Reference Architectures

*How these layers fit together in a space systems platform.*

### The Ground Segment Stack

```
┌─────────────────────────────────────────────────────────────┐
│  AGENCY DATA & APIs                                          │
│  NASA · ESA · ISRO · JAXA · Space-Track · CELESTRAK         │
├─────────────────────────────────────────────────────────────┤
│  SATELLITE VIEW & IMAGERY                                    │
│  Worldview · EO Browser · Zoom Earth · Sentinel Playground  │
├─────────────────────────────────────────────────────────────┤
│  MISSION DESIGN                                              │
│  GMAT + PyKEP + poliastro + SATMO + OpenSat                 │
├─────────────────────────────────────────────────────────────┤
│  FLIGHT DYNAMICS                                             │
│  Orekit + SPICE + Skyfield                                  │
├─────────────────────────────────────────────────────────────┤
│  SSA & TRACKING                                              │
│  SSAPy + Tudat + ASTRA-Core + KeepTrack + SatNOGS           │
├─────────────────────────────────────────────────────────────┤
│  GROUND STATION                                              │
│  Ground Station + SatDump + GNU Radio + TinyGS              │
├─────────────────────────────────────────────────────────────┤
│  MISSION CONTROL                                             │
│  Yamcs / Open MCT / COSMOS / ORQOS                          │
├─────────────────────────────────────────────────────────────┤
│  SPACE WEATHER                                               │
│  NOAA SWPC + ESA SWE + Kamodo + MAGE + PINNBARDS            │
├─────────────────────────────────────────────────────────────┤
│  HUMAN SYSTEMS                                               │
│  NASA HRP + OSDR + H-SPAR DB + MELiSSA + Aerospace Med Calcs│
└─────────────────────────────────────────────────────────────┘
```

### When to Use What

| Scenario | Data Source | Tracking | Ground Station | Mission Control |
|---|---|---|---|---|
| **Amateur cubesat** | CELESTRAK | Gpredict, Look4Sat | SatNOGS + RTL-SDR | Open MCT |
| **University smallsat** | NASA + Space-Track | KeepTrack, SSAPy | SatDump + GNU Radio | Yamcs |
| **Commercial constellation** | Space-Track + NOAA | Tudat, ASTRA-Core | ORQOS, CelesHub | COSMOS, Yamcs |
| **Deep space mission** | JPL Horizons + SPICE | SSAPy, Orekit | DSN-compatible | Open MCT |
| **Space situational awareness** | Space-Track + EU SST | SSAPy, MOCAT, ASTRA | — | Custom |
| **Space weather monitoring** | NOAA SWPC + ESA SWE | — | — | Kamado + MAGE |
| **Human spaceflight** | NASA OSDR + HRP | — | — | Custom |
| **In-space manufacturing** | — | — | — | COSMIC-Roadmap |
