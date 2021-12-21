## Methods to measure spatial access to healthcare facilities in cities
This repo is an Appendix to the Working Paper "Methods to measure spatial access to healthcare facilities in cities: A case study of the urban poor in Chennai". The abstract of the paper can be found below.

## Abstract

Measuring and assessing the spatial access that the urban poor has to public healthcare facilities is critical in planning and improving service delivery in cities. Over the past two decades, studies have introduced a range of spatial methods to do this. However, most of these studies are agnostic to the provider type (private/public) and the target beneficiaries. This study fills that gap by focusing on measuring the access that urban poor have to urban primary health care facilities. It does this by deploying four models – Euclidean distance-based buffer analysis, road network distance-based buffer analysis, Euclidean distance-based nearest facility analysis, and finally, road network distance-based nearest facility analysis. The models are demonstrated for a non-representative sample of slums identified under Rajiv Awas Yojana (RAY) and the urban primary healthcare centres (UPHCs) in the city of Chennai. The study uses replicable open-source GIS-based tools and scripts that can be deployed by other studies. The limitations and computational challenges of each of the models are also briefly discussed. Such studies can generate evidence that feeds into facility planners’ decision making on managing existing facilities and establishing new ones.

This repo contains the scripts that can be used for calculating routes from each settlement to its nearest UPHC (the fourth model discussed in the paper). The input to the scripts is a CSV containing the origin and destination matrix between slums and their nearest facilities generated by the QNEAT plugin in QGIS. 
