
# Global (macroecological?) analysis of ecological networks using open data

## Abstract

## Introduction

Ecological networks are a useful way to think about ecological systems, and recently there has been an explosion of interest in them. This interest has motivated two efforts: an expansion of the tools used to investigate ecological networks, and an increase data collection efforts. In order for both of these efforts to progress, we need a means for ecologists to share and access high-quality network data. Mangal responds to this need, by providing an online database of open network data. Our purpose in the current document is threefold:
1. to describe updates and improvements to the Mangal project
2. to demonstrate the kinds of analyses possible through worked examples
3. to highlight the need for more empirical network data, especially in undersampled regions.

Mangal is an actively developed project which has recently been expanded and improved. An earlier manuscript (Poisot et al 2015 [tk]) set out
* New technical improvements include:
* New data
  - number and amount of new information
* web API for better data access, and two packages (one in Julia, the other in R) for accessing these data.
<!-- I don't think these would literally be a numbered list but it might be a start -->

## Accessing data

Mangal is an open database, meaning that the data included in it can be freely accessed and used by researchers.
<!-- is there an access token required -->

## coverage of Mangal

Users of Mangal will naturally wonder "how much" data are available: where and when were data collected, and for what kind of networks? To demonstrate the coverage of the database, and to demonstrate its use, we show several different views of the data.

### Coverage in geographic space

Mangal now contains information from all over the world, and from every continent except Antarctica.
<!-- map from vignette -->

### Coverage in climate space

Early ecologists identified the earth's biomes based on combinations of temperature and precipitation. Here we demonstrate that Mangal datasets have been sampled from across these different biomes. In doing so, we also demonstrate how climate data can be downloaded and combined with Mangal records.
<!-- Whittaker biome plot -->

### Network types and taxonomy
breakdown of network types (parasitic, mutualistic) and the taxa represented.
<!-- table? or bar chart? -->

## Ecological analyses using Mangal

Ecological networks can be analyzed with a host of different techniques (Delmas et al [tk]). Many (most? [tk]) of these can be calculated using `EcologicalNetworks.jl` (Poisot et al [tk]).

### Link density

### Connectance

## Future of network ecology

### more complete analyses
We have only shown some high-level summaries of the data here; many possibilities remain.

### more data collection
We have demonstrated the considerable coverage of Mangal; however, our summary also highlights important data-collection needs. In particular, we need better information about (mutualists, desert food webs?)

### Active development
This is an open-source project: all data and all code supporting this are available on the Mangal project GitHub organization. Our hope is that the success of this project will encourage similar efforts within other parts of the ecological community.
In addition, we hope that this project will encourage the recognition of the contribution that software creators make to ecological research.

# References
