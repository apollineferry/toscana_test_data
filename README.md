# toscana_test_data

## Description 
toscana_test_data is a set of files used in the test script of the sibling package [toscana](https://github.com/locie/toscana). 

## Usage

These files serve as an example of how to use the `toscana` package, specifically to generate the solar cadastre for the municipality of *La Croix-de-la-Rochette*.

## Content

This collection of files includes:
- Building footprints : _BATIMENT_
- Municipality footprints : _COMMUNE._
- A DEM (Digital Elevation Model) : _N245E400.tif_

These datasets can also be acquired as follows:
- The shapefiles _BATIMENT_ and _COMMUNE_ can be obtained by downloading the dataset from the BDTOPO for departement 73 ([IGN database](https://geoservices.ign.fr/bdtopo)).\
    - _COMMUNE.shp_ is located in the subfolder  : "/BDTOPO/1_DONNEES_LIVRAISON_XXXX-XX-XXXXX/BDT_X-X_SHP_LAMB93_D073-EDXXXX-XX-XX/ADMINISTRATIF/". \
    - _BATI.shp_ is located in the subfolder : "/BDTOPO/1_DONNEES_LIVRAISON_XXXX-XX-XXXXX/BDT_X-X_SHP_LAMB93_D073-EDXXXX-XX-XX/BATI/".\
    - XXXX represents numbers that depend on the version of the dataset. \
- The raster file _N245E400.tif_ can be downloaded from [OpenDem](https://www.opendem.info/opendemeu_download_highres.html).
