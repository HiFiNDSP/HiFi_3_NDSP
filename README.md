
# HiFi_3_NDSP
* NatureDSP Library for HiFi 3/3Z DSP cores
* The source code and xws is common to both HiFi-3 and HiFi-3Z cores. 
* Select approriate core (HiFi-3 or HiFi-3Z) while building for both xws and linux evvironments. 

# The repo is organized as follows.

## xws:
  * Last stable release version of the NDSP containing two xws files.

  * An xws each, for the library-kernels and the test-driver.
    Ex : HiFi3_VFPU_Library_v4_1_0.xws & HiFi1_VFPU_Demo_v4_1_0.xws

  * Building and executing the xws in Xtensa Xplorer is described in the API Reference Document. 
  * Detailed release documentation can be extracted from lib.xws/doc folder.

### Release v4.1.0 Brief: 
  * Release Date : 16-May-2022.  
  * Functional changes : added SFPU support for floating point routines
  * API/doc changes: None
  * The code and xws have been tested only with a limited number of HiFi-3/3Z configurations in RI-2022.10 tool chain. 
  * Added LMS convergence tests
  * Added more FFT tests
  * Added sanity vectors for quick functional check
  * Fixed scratch allocation errors in some FIR functions
  * Fixed saturation error in imdct8x16()
  * Performance improvements for FFT routines
    

## NDSP_HiFi3
* This contains the source code along with make files that will build in linux environment.  


## doc folder
This contains help documentation on how to build the source code in linux and run the performance and functional regressions. 
