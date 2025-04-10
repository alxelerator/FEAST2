# FEAST2
Optimized FEAST microbiome source tracking [work in progress]

This package extends and contains slightly tweaked/debugged versions of scripts of the FEAST package from [cozygene github](https://github.com/cozygene/FEAST) (not updated last 5 years).

Thus far there are no REAL algorithm tweaks, just better handling of folders and files avoiding setwd() stuff complicating and failing iterations if we want to.  

*Note!* The algorithm is fearly sensitive to missing/incomplete data!

Extension is foreseen to include sensitive analysis (after I cleaned up my working scripts doing the job).


# FEAST - a scalable algorithm for quantifying the origins of complex microbial communities
A major challenge of analyzing the compositional structure of microbiome data is identifying its potential origins. Here, we introduce Fast Expectation-mAximization microbial Source Tracking (FEAST), a ready-to-use scalable framework that can simultaneously estimate the contribution of thousands of potential source environments in a timely manner, thereby helping unravel the origins of complex microbial communities. The information gained from FEAST may provide insight into quantifying contamination, tracking the formation of developing microbial communities, as well as distinguishing and characterizing bacteria-related health conditions. For more details see Shenhav et al., Nature Methods 2019 (https://www.nature.com/articles/s41592-019-0431-x).

# Installation
Original FEAST should be available on QIIME 2 at some time.... but currently 2025-april-10 it is still not there...

<u>Our</u> updated FEAST2 version can be installed using devtools:

`devtools::install_github("alxelerator/FEAST2")`


# Usage

My updated usage instructions will follow soon.  


