
# HiFi_3_NDSP
* NatureDSP Library for HiFi 3/3Z DSP cores
* The source code and xws is common to both HiFi-3 and HiFi-3Z cores. 
* Select approriate core (HiFi-3 or HiFi-3Z) while building, for both xws and linux evvironments. 

# The repo is organized as follows.

## xws:
  * Last stable release version of the NDSP containing two xws files.
  * An xws each, for the library-kernels and the test-driver.
    Ex : HiFi3_VFPU_Library_v4_1_0.xws & HiFi1_VFPU_Demo_v4_1_0.xws
  * Building and executing the xws in Xtensa Xplorer is described in the API Reference Document. 
  * Detailed release documentation can be extracted from lib.xws/doc folder.

### Release v4.1.0 Brief: 
* The source code has been tested with a limited number of HiFi-3 and HiFi-3z cores, 
  using the RI-2022.10 tool chain.
* Performance data:
  The performance and the API reference document remains the same as the earlier release. 
* Known issues: None.
   
## NDSP_HiFi3
* This contains the source code along with make files that will build in linux environment.  

## doc folder
This contains help documentation on how to build the source code in linux and run the performance and functional regressions. 
