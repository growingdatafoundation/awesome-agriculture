# Awesome Agriculture [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome open source technology for agriculture, farming, and gardening.

[Agriculture](https://en.wikipedia.org/wiki/Agriculture) is the science and art of cultivating plants and livestock for food and materials.

Contributions welcome! Please follow the [contributing guidelines](https://github.com/growingdatafoundation/awesome-agriculture/blob/master/contributing.md).

## Contents

- [Automation and Robotics](#automation-and-robotics)
- [Calculators](#calculators)
- [Climate, Environment and Weather](#climate-environment-and-weather)
- [Crop Modeling, Phenotyping, and Pathology](#crop-modeling-phenotyping-and-pathology)
- [Datasets](#datasets)
- [Data Standardization, Interoperability and APIs](#data-standardization-interoperability-and-apis)
- [Farm Management Systems and Record Keeping](#farm-management-systems-and-record-keeping)
- [Geospatial and GIS](#geospatial-and-gis)
- [IoT, Hardware](#iot-hardware)
- [Knowledgebases and Learning Resources](#knowledgebases-and-learning-resources)
- [Machine Learning and AI](#machine-learning-and-ai)
- [Markets and Food Systems](#markets-and-food-systems)
- [Remote Sensing and Imagery](#remote-sensing-and-imagery)

## Automation and Robotics

Open hardware and software for agricultural robots and autonomous vehicles, from small weeding platforms to coverage path planning for tractors.

- [Acorn Rover](https://github.com/Twisted-Fields) - precision farming rover, Odrive, Python.
- [Ant Robotics](https://antrobotics.de/) - development from Ecoterra bot
- [Earth Rover](https://github.com/earthrover) - Ag AGV ROS1 precision farming rover 
- [EcoTerra Bot](https://ecoterrabot.com/) - Delta & Rover
- [FarmBot](https://github.com/farmbot) - Open source precision gardening project.
- [FarmBot-ROS](https://github.com/farmbot-ros/) - Open source farming robot.
- [Field Friend](https://github.com/zauberzeug/feldfreund_devkit) - A Development Platform for Autonomous Weeding. 
- [Fields2Cover](https://github.com/Fields2Cover/Fields2Cover) - Robust and efficient coverage paths for autonomous agricultural vehicles.
- [Romi project](https://media.romi-project.eu/documents/index.html) - Europe-funded research project 
- [ROS Agriculture](http://rosagriculture.org/) - Open Source community focusing on using Robot Operating System to empower farmers with robotics tools. 
- [Sowbot](https://github.com/Agroecology-Lab/Sowbot) - Open-hardware seeding and weeding robot for smallholder agroecological farms, with a ROS 2 stack.
- [Weedinator](https://hackaday.io/project/53896-weedinator-2019) - Line following weeding robot

## Calculators

Tools that turn agronomic formulas into quick answers for everyday farm decisions.

- [farm-calculators](https://github.com/brycejohnston/farm-calculators) - WordPress plugin for calculating various farming and crop related information.

## Climate, Environment and Weather

Libraries, datasets and services for weather, evapotranspiration and soil data: the environmental inputs behind irrigation, planting and crop models.

- [agroclimatology](https://github.com/brycejohnston/agroclimatology) - Ruby client for interacting with the NASA (POWER) Agroclimatology Web Resource.
- [evapotranspiration](https://github.com/brycejohnston/evapotranspiration) - Ruby library for calculating reference crop evapotranspiration (ETo).
- [frostline](https://github.com/waldoj/frostline) - A dataset, API, and python parser for USDA plant hardiness zones.
- [GSODR](https://github.com/ropensci/GSODR) - Global summary daily weather data in R.
- [iem](https://github.com/akrherz/iem) - Code that makes the Iowa Environmental Mesonet run.
- [MAgPIE](https://github.com/magpiemodel/magpie) - Global land-use allocation model linking agricultural production, land use and environmental impacts.
- [PyETo](https://github.com/woodcrafty/PyETo) - Python package for calculating reference/potential evapotranspiration (ETo).
- [pyTSEB](https://github.com/hectornieto/pyTSEB) - A python two source energy balance model for estimation of evapotranspiration with remote sensing data.
- [soilDB](https://github.com/ncss-tech/soilDB) - R library for simplified access to NCSS soil databases.
- [SoilHive Core](https://github.com/varda-ag/soilhive-core) - Federated platform for discovering, harmonising and sharing soil datasets across institutions.

## Crop Modeling, Phenotyping, and Pathology

Communities and tools for simulating crop growth, measuring plant traits and studying plant disease.

- [apsimNGpy](https://github.com/MAGALA-RICHARD/apsimNGpy) - Python interface for running and analysing APSIM Next Generation simulations.
- [CroptimizR](https://github.com/SticsRPacks/CroptimizR) - R package for parameter estimation and uncertainty analysis of crop models.
- [DSSAT](https://github.com/DSSAT/dssat-csm-os) - Decision Support System for Agrotechnology Transfer cropping system model.
- [Epicrop.jl](https://codeberg.org/adamhsparks/Epicrop.jl) - Crop disease epidemic simulation using a compartmental (HLIP) model, in Julia.
- [FielDHub](https://github.com/DidierMurilloF/FielDHub) - R/Shiny app for designing agricultural field experiments.
- [Open Plant Pathology](https://github.com/openplantpathology) - A community that values open data and computational tools for advancing epidemiology and pathogen population biology and ecology.
- [Phenomenal](https://github.com/openalea/phenomenal) - 3D plant phenotyping and organ segmentation from multi-view images.
- [PlantGL](https://github.com/openalea/plantgl) - Geometric library for modelling and visualising plant architecture.

## Datasets

Openly available agricultural datasets for research, model training and benchmarking, from field imagery and crop-type labels to yield records.

- [Agriculture Datasets Collection](https://lacunafund.org/datasets/agriculture/) - Curated collection of machine learning datasets specifically designed to address food security challenges in developing regions.
- [CEAOD](https://ceaod.github.io/) - Controlled Environment Agriculture Open Data repository providing standardized datasets for greenhouse and indoor farming research with data analysis tools.
- [CropHarvest](https://github.com/nasaharvest/cropharvest) - Open source remote sensing dataset for global crop type mapping with 95,186 labeled datapoints from satellite imagery, supporting machine learning research for food security.
- [CWFID](https://github.com/cwfid/dataset) - Dataset comprising field images, vegetation segmentation masks and crop/weed plant type annotations.
- [FAO/NASA Harvest Crop Type Dataset](https://data.harvestportal.org/dataset/fao-bha-nasa-harvest-public-crop-type-datasets) - Ground truth crop type observations dataset with geolocated field data for validation and training of cropland classification models.
- [Growstuff](https://www.growstuff.org/crops) - Record keeping & crop database, nice API
- [PlantVillage](https://www.kaggle.com/datasets/emmarex/plantdisease) - Dataset containing leaf images of healthy and diseased plants, covering 38 disease classes across 14 different crops.
- [SoybeanYield](https://github.com/saeedkhaki92/CNN-RNN-Yield-Prediction?tab=readme-ov-file) - A multimodal agricultural dataset for soybean yield forecasting, integrating yield performance, management practices, weather data, and soil parameters. 
- [TERRA REF](https://terraref.org) - 1PB public domain high resolution sensor data from sorghum breeding trials ([data publication](https://doi.org/10.5061/dryad.4b8gtht99) with large files available on [globus.org at ncsa#terra-public](https://app.globus.org/file-manager?origin_id=e8feaff4-96cd-11ea-bf90-0e6cccbb0103&origin_path=%2F))

## Data Standardization, Interoperability and APIs

Standards, frameworks and API examples that help farm software, machinery and services exchange data. Several entries are vendor code samples rather than standards in their own right.

- [AgGateway’s ADAPT Toolkit](https://adaptframework.org) - Open Source project providing tools to simplify communication between growers, their machines, and their partners.
- [Agstack](https://github.com/agstack) - Open-Source Digital Infrastructure for the Agriculture Ecosystem.
- [API-Code-Samples](https://github.com/aWhereAPI/API-Code-Samples) - Contains aWhere's API platform code samples.
- [Botanica](https://github.com/Michael-A-Kuykendall/botanica) - Production-ready Rust crate for professional botanical data management with taxonomic hierarchy, cultivation tracking, and Darwin Core compliance.
- [ClearAg-API-Examples](https://github.com/IterisClearAg/ClearAg-API-Examples) - A collection of code examples using the ClearAg APIs.
- [Fiware AgriFood](https://www.fiware.org/community/smart-agrifood/) - Open Source data standards and IoT framework that help connect farm systems and enable practical smart farming and agrifood solutions—part of the larger Fiware.org project.
- [FoodOn](https://github.com/FoodOntology/foodon) - Open ontology for food, food sources and food processing.
- [JDLinkMachineDataAPI-OAuth2-CSharp-Example](https://github.com/JohnDeere/JDLinkMachineDataAPI-OAuth2-CSharp-Example) - CSharp JDLink Machine Data API client example.
- [MyJohnDeereAPI-OAuth2-Java-Example](https://github.com/JohnDeere/MyJohnDeereAPI-OAuth2-Java-Example) - Java MyJohnDeere API client example.
- [MyJohnDeereAPI-OAuth2-NodeJS-Example](https://github.com/JohnDeere/MyJohnDeereAPI-OAuth2-NodeJS-Example) - Node.js MyJohnDeere API client example.
- [MyJohnDeereAPI-OAuth2-Python-Example](https://github.com/JohnDeere/MyJohnDeereAPI-OAuth2-Python-Example) - Python MyJohnDeere API client example.
- [Open Ag Data Alliance](https://github.com/oada) - OADA is an open project designed to bring interoperability, security, and privacy to agricultural data.
- [Open Agri Common Semantic Model (OCSM)](https://github.com/agstack/OpenAgri-OCSM) - OCSM is an ontology based on the modular reuse of existing standards providing the basis for semantic interoperability across smart farming solutions. 
- [Open-Agriculture](https://github.com/Open-Agriculture) - Free and open source ISOBUS (ISO 11783) tools, including the AgIsoStack++ library, a Virtual Terminal, a DDOP editor and a VT object pool designer.
- [OpenTeam](https://openteam.community/) - Open Technology Ecosystem for Agricultural Management
- [SampleData](https://github.com/JohnDeere/SampleData) - Sample datacards, shapefiles, and other files you can use for testing.
- [SencropAPI-JavaScript-Client](https://github.com/sencrop/sencrop-js-api-client) - Sencrop API Javascript client implementation. Read and manage Sencrop weather stations.

## Farm Management Systems and Record Keeping

Applications for planning, recording and reporting farm activities, from market gardens to larger mixed enterprises.

- [AnimalTrakker](https://gitlab.com/animaltrakker_system/animaltrakker_farm_mobile) - Mobile record keeping for sheep and goat flocks.
- [DigiAgriApp](https://gitlab.com/digiagriapp/digiagriapp-server) - Field and orchard data management server with sensor and remote-sensing integration.
- [Ekylibre](https://github.com/ekylibre/ekylibre) - Farm management information system for farmers and small enterprises built with Ruby on Rails and PostgreSQL/PostGIS.
- [farmOS](https://github.com/farmOS/farmOS) - Web-based farm record keeping application built with Drupal and PHP.
- [GrowGood](https://gitlab.com/growgood) - GrowGood is an open-source farm management platform using open standards like ValueFlows and JSON-LD to help track and share interoperable data across agricultural operations and marketplaces.
- [LiteFarm](https://github.com/LiteFarmOrg/LiteFarm) - LiteFarm is the world’s first community-led, not-for-profit, Farm management system
- [Soil Mate](https://github.com/Open-Source-Agriculture/soil_mate) - Helper app designed to assist the collection of soil data.
- [Tania](https://github.com/Tanibox/tania-core) - Free and open source farming management system for everyone built with Go and Vue.js.


## Geospatial and GIS

General-purpose GIS platforms and libraries that agricultural tools commonly build on, plus pointers to broader GIS lists.

### GIS Resources

- [Awesome GIS](https://github.com/sshuair/awesome-gis) - Awesome GIS is a list collecting abundant GIS related sources.

### GIS Platforms

- [AI Segmentation by TerraLab](https://github.com/TerraLabAI/QGIS_AI-Segmentation) - Free QGIS plugin that segments fields, trees, buildings and any object from satellite and drone imagery into vector polygons with one click.
- [QGIS](https://qgis.org) - QGIS is a free, open source, cross platform (lin/win/mac) geographical information system.

### Shapefiles

- [pyshp](https://github.com/GeospatialPython/pyshp) - Reads and writes ESRI Shapefiles in pure Python.
- [rgeo-shapefile](https://github.com/rgeo/rgeo-shapefile) - RGeo Shapefile is an optional module for RGeo for reading geospatial data from ESRI shapefiles in Ruby.

## IoT, Hardware

Sensors, controllers and guidance systems that farmers and makers can build, adapt and run themselves.

- [AgOpenGPS](https://github.com/AgOpenGPS-Official/AgOpenGPS) - Ag precision mapping and section control software.
- [Farm Hack](https://farmhack.org/tools) - Worldwide community of farmers that build and modify our own tools.
- [Farm-Data-Relay-System](https://github.com/timmbogner/Farm-Data-Relay-System) - System using ESP-NOW, LoRa, and other protocols to transport sensor data in remote areas without relying on WiFi.
- [Mycodo](https://github.com/kizniche/Mycodo) - Environmental monitoring and regulation for mushrooms, hydroponics and greenhouses.
- [Open Agriculture Foundation](https://github.com/OpenAgricultureFoundation) -  Open Source ecosystem of technologies that enable and promote transparency, networked experimentation, education, and hyper-local production.
- [Open hydroponics](https://openhydroponics.com/) - Fully Automated Hydroponic OS 
- [OpenMinder](https://github.com/autogrow/openminder) - Open Source Rootzone Monitoring, API and open source hat for the RaspberryPi.
- [OpenSprinkler](https://github.com/OpenSprinkler/OpenSprinkler-Firmware) - Firmware for the open irrigation controller.
- [OpenWeedLocator](https://github.com/geezacoleman/OpenWeedLocator) - Open Source, low-cost, image-based weed detection device for in-crop and fallow scenarios.
- [Simplesteer](https://github.com/matmis/simplesteer) - RTK GPS tractor autosteer system with a web interface that you can control with a smartphone and can run on a Raspberry Pi.
- [Smart Farming Thingsboard](https://github.com/arifulmrislam/Smart-farming-dashboard-with-ThingsBoard) - a demo smart farming project using ThingsBoard to collect sensor data and display it on real-time agricultural dashboards.
- [Smart Irrigation](https://github.com/altmenorg/HAsmartirrigation) - Home Assistant integration that schedules irrigation from evapotranspiration.

## Knowledgebases and Learning Resources

Open databases and guides on growing plants and producing food.

- [Harvest Helper](https://github.com/damwhit/harvest_helper) -  Provides growing, harvesting and recipe information for the 45 plants in the database as well as a JSON API.
- [OpenFarm](https://github.com/openfarmcc/OpenFarm) - A free and open database for farming and gardening knowledge built with Ruby on Rails.

## Machine Learning and AI

Frameworks, models and tutorials that apply machine learning to agricultural problems such as yield prediction and plant phenotyping.

- [AgML](https://github.com/Project-AgML/AgML) - Centralized framework for agricultural machine learning.
- [agridat](https://github.com/kwstat/agridat) - R package providing an extensive collection of datasets from agricultural experiments.
- [Crop Yield Prediction](https://github.com/JiaxuanYou/crop_yield_prediction) - Deep gaussian process for crop yield prediction based on remote sensing data.
- [Deep Learning for Biologists with Keras](https://github.com/totti0223/deep_learning_for_biologists_with_keras) - Tutorials for deep learning based analysis (mainly) on biological relavent themes.
- [FarmVibes.AI](https://github.com/microsoft/farmvibes-ai) - Multi-Modal GeoSpatial ML Models for Agriculture and Sustainability.
- [PlantCV](https://github.com/danforthcenter/plantcv) - Plant phenotyping software using computer vision.

## Markets and Food Systems

Software for moving food beyond the farm gate: farmer marketplaces, food co-ops, community-supported agriculture (CSA) administration and food rescue.

- [FoodCoopShop](https://github.com/foodcoopshop/foodcoopshop) - Ordering and stock software for food co-ops and local farm shops.
- [foodsharing](https://gitlab.com/foodsharing-dev/foodsharing) - Platform behind foodsharing.de, coordinating volunteers who rescue surplus food.
- [Foodsoft](https://github.com/foodcoops/foodsoft) - Ordering, accounting and member management for non-profit food co-ops.
- [Juntagrico](https://github.com/juntagrico/juntagrico) - Management platform for community-supported agriculture: memberships, shares, deliveries and work shifts.
- [Karrot](https://codeberg.org/karrot/karrot-frontend) - Organising tool for grassroots groups that save and share food.
- [Open Food Network](https://github.com/openfoodfoundation/openfoodnetwork) - Online marketplace for farmers and food hubs to sell directly to eaters.
- [OpenOlitor](https://github.com/OpenOlitor/openolitor-server) - Administration software for community-supported agriculture initiatives.
- [Teikei](https://github.com/teikei/teikei) - Map platform connecting consumers with community-supported agriculture (CSA) farms.

## Remote Sensing and Imagery

Tools and curated lists for processing satellite, aerial and drone imagery of crops and land.

- [Awesome Sentinel](https://github.com/Fernerkundung/awesome-sentinel) - A curated list of awesome tools, tutorials and APIs related to data from the Copernicus Sentinel Satellites.
- [Awesome Vegetation Index](https://github.com/px39n/Awesome-Vegetation-Index) - List of reference, applications of common Vegetation Indices for Multi-spectral, hyper-spectral and UAV images.
- [OpenDroneMap](https://github.com/OpenDroneMap/ODM) - Drone image processing into orthomosaics, elevation models and plant health maps.
- [Raster Vision](https://github.com/azavea/raster-vision) - Deep learning for aerial/satellite imagery.
- [Sen2Agri](https://github.com/Sen2Agri/Sen2Agri-System) - Software system processing high resolution satellite images for agricultural purposes.
- [WebODM](https://github.com/WebODM/WebODM) - Web interface for processing and sharing OpenDroneMap drone surveys.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Bryce Johnston](https://github.com/brycejohnston) has waived all copyright and related or neighboring rights to this work.
