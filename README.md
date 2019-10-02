

# Awesome Cryosphere Software and Data [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A prototype of a curated list of awesome data sources, models, tools and organizations related to the Cryosphere and its subspheres.


## Contents
- [Cryosphere - across all subspheres](#cryosphereacrossallsubspheres)
    - [Software](#caas-software)
    - [Data](#caas-data)
- [Frozen Ground/Permafrost](#frozengroundpermafrost)
    - [Software](#fgp-software)
    - [Data](#fgp-data)
- [Glacier and Ice Sheets](#glaciersandicesheets)
    - [Software](#gis-software)
            - [Open Source Models](#gis-software-os) 
            - [Closed/On-Demand Source Models](#gis-software-cs) 
    - [Data](#gis-data)
	    - [Global Data](#gis-globaldata) 
	    - [National Data](#gis-localdata)
	        - [Switzerland](#gis-swissdata)
- [Sea Ice](#seaice)
    - [Software](#si-software)
    - [Data](#si-data)
- [Snow](#snow)
    - [Software](#s-software)
    - [Data](#s-data)
- [Contributing](#contributing)
- [License](#license)

## Cryosphere - across all subspheres
### Software
### Data 
## Frozen Ground/Permafrost
### Software
### Data

## Glaciers and Ice Sheets

### Software

####  Open Source Models 

##### Ice Flow and Mass Balance
- [ALPGM](https://github.com/JordiBolibar/ALPGM) - ALpine Parameterized Glacier Model
- [CISM](https://github.com/CISM/cism) - Community Ice Sheet Model
- [DEISM ice-sheet-model](https://github.com/cpk26/ice-sheet-model) - DEpth integrated Ice Sheet Model (DEISM)
- [Elmer/Ice](https://github.com/elmercsc/elmerfem) - Open Source Finite Element Software for Ice Sheet, Glaciers and Ice Flow Modelling
- [flowline-glacier-model](https://github.com/aaschwanden/flowline-glacier-model) - Flowline glacier model by Andy Aschwanden
- [glacier-flow-model](https://github.com/munterfinger/glacier-flow-model) - Modelling glacier flow, based on the glaciers mass balance and a digital elevation model
- [GRANTISM](http://homepages.ulb.ac.be/~fpattyn/grantism/)  - GReenland & ANTarctic Ice Sheet Model + Svalbard extension
- [icepack](https://github.com/icepack/icepack) - Finite element modeling of glaciers and ice sheets
- [icetools](https://github.com/alexjarosch/icetools) - icetools provides a development environment for numerical ice flow models/simulations
- [ISSM](https://issm.jpl.nasa.gov/)  - Ice Sheet System Model
- [js-ism](https://github.com/mewo2/js-ism) - A simple Javascript ice sheet model
- [MPAS-Albany Land Ice (MALI)](https://github.com/MPAS-Dev/MPAS-Release/releases) - a variable-resolution ice sheet model for earth system modeling using voronoi grids
- [OGGM](https://oggm.org/) - Open Global Glacier Model: a modular open source model for glacier dynamics
- [PISM](http://www.pism-docs.org/wiki/doku.php) - Parallel Ice Sheet Model
- [PyGEM](https://github.com/drounce/PyGEM) - Python Glacier Evolution Model (PyGEM)
- [sia-fluxlim](https://github.com/alexjarosch/sia-fluxlim) - Implementation of a MUSCL-superbee flux limiter to a shallow ice approximation flow code based on finite differences
- [SICOPOLIS](http://www.sicopolis.net/)  - SImulation COde for POLythermal Ice Sheets
- [speceis_flowline](https://github.com/douglas-brinkerhoff/speceis_flowline) - Width-parameterized flowline version of the spectral ice sheet model (SpecEIS)
- [Úa](https://github.com/GHilmarG/UaSource) - A large-scale ice-flow model
- [VarGlaS](https://github.com/douglas-brinkerhoff/VarGlaS) - The source code repository for the Variational Glacier Simulator (VarGlaS) code
- [Yelmo](https://github.com/palma-ice/yelmo) - a 3D ice-sheet-shelf model solving for the coupled dynamics and thermodynamics of the ice sheet system



##### (Surface) Mass Balance only
- [pypdd](https://github.com/juseg/pypdd) - A positive degree day model for glacier surface mass balance

##### Calving/Frontal Ablation
- [cryo_calving_2019](https://github.com/bearecinos/cryo_calving_2019) - Experiments with a minimal Frontal ablation model added to OGGM
- [HiDEM](https://github.com/joeatodd/HiDEM) - Helsinki Discrete Element Model, a particle model for simulating elastic behaviour, fracture and calving at marine terminating glaciers

##### Hydrology
- [CCHF](https://github.com/thomasmosier/CCHF) - Cryosphere hydrology modeling package written in Matlab
- [DEBAM/DETIM](https://github.com/regine/meltmodel)  - Distributed Energy Balance Model (DEBAM) and Distributed Enhanced Temperature Index Model (DETIM): Two Distributed Glacier Surface Mass-Balance and Discharge Models

##### Sub-/Englacial Hydrology
- [1Dhydro](https://bitbucket.org/maurow/1dhydro/src/master/) - Example subglacial hydrology model for teaching. Subglacial processes workshop at Centre for Ice and Climate, The Niels Bohr Institute, University of Copenhagen 7-11 th April 2014
- [RchannelODE.jl](https://bitbucket.org/maurow/rchannelode.jl/src/master/) - Solves the 1D steady state R-channel equations
- [SHAKTI](https://issm.jpl.nasa.gov/download/) - Subglacial hydrology and kinetic transient interactions

##### Miscellaneous
- [bod-marine](https://github.com/bueler/bod-marine) - exact solution to marine ice sheet 1D problem, coming from Bodvardsson (1955)
- [debadvect](https://github.com/awirbel/debadvect) - FEM model for englacial debris transport
- [Glacier initialization](https://github.com/OGGM/initialization) - Method to reconstruct estimated glacier states up to 1850
- [Glacier reconstruction](https://github.com/juliaeis/reconstruction) - Reconstruction of estimated glacier states
- [GlacialLakeHazards](https://github.com/drounce/GlacialLakeHazards) - Matlab codes from PhD work on glacial lake outburst flood hazards in the Nepal Himalaya
- [icepack-py](https://github.com/danshapero/icepack-py) - Python bindings and utility scripts for icepack
- [mb_crossval](https://github.com/OGGM/mb_crossval) - Code for the continuous mass-balance cross-validation tool
- [Rounce2014_debristhickness](https://github.com/drounce/Rounce2014_debristhickness) - Codes associated with deriving the debris thickness of debris-covered glaciers from Landsat thermal imagery
- [sia-fve](https://github.com/bueler/sia-fve) - implicit finite volume element (FVE) method for the shallow ice approximation (SIA) free-boundary problem



####  Closed/On-Demand Source Models

##### Ice Flow and Mass Balance
- [GagliardiniWerder2018](https://doi.org/10.1017/jog.2018.59) - Influence of an increasing surface melt over decadal timescales on land terminating outlet glaciers (paper)
- [GloGEM](https://doi.org/10.3389/feart.2015.00054) - A model for global glacier change and sea-level rise
- [GloGEMflow](https://doi.org/10.5194/tc-13-1125-2019) - Extended version of the Global Glacier Evolution Model (GloGEM), in which both surface mass balance and ice flow are explicitly accounted for
- [GERM](http://dx.doi.org/10.1002/hyp.8276) - Glacier Evolution and Runoff Model


##### Sub-/Englacial Hydrology
- [Beyeretal2017](https://doi.org/10.5194/tc-12-3931-2018) - A confined–unconfined aquifer model for subglacial hydrology and its application to the north east Greenland ice stream (paper)
- [Brinkerhoffetal2011](https://doi.org/10.1017/aog.2016.3) - Inversion of a glacier hydrology model (paper)
- [BuelervanPelt2015](https://doi.org/10.5194/gmd-8-1613-2015) - Mass-conserving subglacial hydrology in the Parallel Ice Sheet Model version 0.6 (paper)
- [deFleurian2016](https://doi.org/10.1002/2016JF003842) - A modeling study of the effect of runoff variability on the effective pressure beneath Russell Glacier, West Greenland (paper)
- [Hewitt2017](https://doi.org/10.3189/002214311796405951) - Modelling distributed and channelized subglacial drainage: the spacing of channels (paper)
- [HoffmanPrice2014](https://doi.org/10.1002/2013JF002943) - Feedbacks between coupled subglacial
hydrology and glacier dynamics (paper)
- [KesslerAnderson2004](https://doi.org/10.1029/2004GL020622) - Testing a numerical glacial hydrological model using spring speed‐up events and outburst floods (paper)
- [PimentelFlowers2010](https://doi.org/10.1098/rspa.2010.0211) - A numerical study of hydrologically driven glacier dynamics and subglacial flooding (paper)
- [Werderetal2013](https://doi.org/10.1002/jgrf.20146) - Modeling channelized and distributed subglacial drainage in two dimensions (paper)


#### Visualization Tools
- [GLIMS Glacier Viewer](http://www.glims.org/maps/glims) - Global Land Ice Measurememts from Space (GLIMS) / Global Terrestrial Network for Glaciers (GTN-G) Glacier Viewer covering a range of inventories
- [OGGM Dash](https://dash.klima.uni-bremen.de/) - Three worldwide glacier visualization Apps developed at a Hackathon
- [WGMS Smartphone App](https://wgms.ch/glacierapp/) - Browsing glaciers worldwide and in your proximity
- [WGMS FoG Browser](https://wgms.ch/fogbrowser/) - Fluctuations of Glaciers Dataset Browser
- [GLAMOS](https://glamos.ch) - Browsing Swiss glaciers on an interactive map
- [iceplotlib](https://github.com/juseg/iceplotlib) - Plotting tools for PISM using matplotlib and netcdf4-python


### Data
#### Global Data
- [FoG](https://wgms.ch/data_databaseversions/) - Fluctuations of Glaciers with point, elevation band and specific mass balance measurements 
- [Glacier Length Fluctuations](https://folk.uio.no/paulwl/length.php)  - Glacier Length Database by Paul Leclercq
- [GlaThiDa](https://www.gtn-g.ch/data_catalogue_glathida/)  - Glacier Thickness Dataset with point, elevation band and specific ice thickness measurements
- [RGI](http://www.glims.org/RGI/index.html) - Randolph Glacier Inventory
- [WGI](https://nsidc.org/data/g01130)  - World Glacier Inventory

#### National Data
##### Switzerland
- [GLAMOS](https://glamos.ch) - Glacier Monitoring Switzerland: the Swiss glacier data portal

## Sea Ice
### Software
- [CICE](https://github.com/CICE-Consortium/CICE) - CICE sea-ice model
- [Icepack](https://github.com/CICE-Consortium/Icepack) - sea-ice column physics
- [SIS2](https://github.com/NOAA-GFDL/SIS2) - NOAA-GFDL's Sea Ice Simulator version 2
### Data 

## Snow
### Software
- [SNOWPACK](https://models.slf.ch/p/snowpack/)  - multi-purpose snow and land-surface model
- [cosipy](https://github.com/cryotools/cosipy) - Coupled snowpack and ice surface energy and mass balance model in Python
- [FSM2](https://github.com/RichardEssery/FSM2) - Flexible Snow Model: a multi-physics energy balance model of accumulation and melt of snow on the ground and in forest canopies
- [snowtools](https://github.com/dshean/snowtools) - D. Shean's utilities for working with snow data

### Data
#### Global Data
 - [CommunitySnowObs](http://communitysnowobs.org/) - Community Snow Observations

## Educational Tools and Data
- [OGGM-edu](http://edu.oggm.org/en/latest/) - Educational material about glaciers, powered by OGGM and MyBinder
- [glacier-graphics](https://github.com/OGGM/glacier-graphics) - A collection of glacier graphics that can be used for education and outreach
- [Ed Bueler's Karthaus material](https://github.com/bueler/karthaus) - Notes and codes for Ed Bueler's numerical lectures at Karthaus (Italy) Summer School on Ice Sheets and Glaciers
- [Ed Bueler's McCarthy material](https://github.com/bueler/mccarthy) - Ed Bueler's slides, notes, and codes on numerical glacier and ice sheet modeling, for the International Summer School in Glaciology, McCarthy, AK
- [UW_Geodetic_Mass_Budget_Scripts](https://github.com/ShashankBice/UW_Geodetic_Mass_Budget_Scripts) - no description provided
- [Andy Aschwanden's McCarthy material](https://github.com/aaschwanden/mccarthy-summerschool) - International Summer School in Glaciology, McCarthy, AK. Lecture notes and excercises by Andy Aschwanden
- [Glaciers Dynamics Lecture](https://github.com/aaschwanden/glaciers617) - Glacier Dynamics lecture by Andy Aschwanden
- [icepack-examples](https://github.com/danshapero/icepack-examples) - Example code for the glacier modelling library icepack
- [Lindsey Nicholson's teaching](https://github.com/linznicholson/teaching) - Materials Lindsey developed for teaching (mainly) about glaciers
- [Physics of Glacier lecture at ETH](http://people.ee.ethz.ch/~luethim/teaching.html) - All the course material for the "Physics of Glaciers" class.
- [Subglacial processes workshop material](https://maurow.bitbucket.io/teaching/copenhagen2014.html) - Mauro Werder's material from the subglacial processes workshop Copenhagen
- [Swisseduc Glaciers online](https://www.swisseduc.ch/glaciers/) - A collection of photos and processes of different glaciers


# Contributing

- Please check for duplicates first.
- Keep an alphabetical order if there is more than one entry in your category
- Keep descriptions short, simple and unbiased.
- Please make an individual commit for each suggestion
- Add a new category if needed.

Thanks for your suggestions!


# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
