# sample

This repository contains the following files that are associated with the Alter et al. manuscript that was submitted to JGR Atmospheres:
1) Scripts for configuring the WRF meteorological model for simulations, and
2) Data to reproduce the figures in the manuscript.

## Authors
Ross E. Alter<sup>1*</sup>, Michelle E. Swearingen<sup>2</sup>, and Mihan H. McKenna Taylor<sup>3</sup> 

<sup>1</sup>U.S. Army Engineer Research and Development Center (ERDC), Cold Regions Research and Engineering Laboratory (CRREL), Hanover, NH, USA.

<sup>2</sup>U.S. Army Engineer Research and Development Center (ERDC), Construction Engineering Research Laboratory (CERL), Champaign, IL, USA.

<sup>3</sup>U.S. Army Engineer Research and Development Center (ERDC), Vicksburg, MS, USA.

## Created
September 2022

## Purpose
This repository contains data used by Alter et al. for the manuscript "The influence of mesoscale atmospheric convection on local infrasound propagation", which has been submitted for publication in JGR Atmospheres.

## Data
This repository contains two directories of files associated with the Alter et al. manuscript:
1.  WRF configuration files

    - The WRF configuration files contain namelist.wps and namelist.input files to run WRF simulations consistent with those in the Alter et al. manuscript.  Each directory is organized by the horizontal resolution of the innermost domain of the associated simulation (e.g., 1-km = innermost domain with 1 km horizontal resolution).

    - *Note*:
      - For the 15-km restart simulation, the model time step was reduced from 135 to 90 seconds to better match the updated model output frequency for the innermost domain (once per 60 seconds).  With this new time step, the time step and model output overlap every two minutes instead of every nine minutes.

2.  Figure data

    - The figure data are the raw data that are used to produce each figure in the Alter et al. manuscript.

    - *Note*:
      - The last row and column of each dataset is not plotted for each of the horizontal maps in Figures 2-5 because of the way in which the datasets and their dimensions are interpreted by pcolormesh in the Basemap library.
