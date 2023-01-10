# REPPU-ESN
The machine learning based surrogate model for the ionospheric outputs from REPPU global MHD simulation is developed using the echo state network (ESN, e.g., [Tanaka et al., Phys. Rev. Res. 2022](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.4.L032014)). The python codes and the dataset for the ESN-based emulator model (Kataoka et al., 2023, submitted to GRL) are provided here.  

  ## Folders
  * emulator: this folder contains the dataset, a sample code, and a demo for reproducing Fig. 3 in the reference paper.

  ## Usage
  Some python modules, such as numpy, scipy, matplotlib, and networkx, as well as [esn_dts_openloop.py](https://github.com/GTANAKA-LAB/DTS-ES), are required to run the codes. 
  
  ## Developer
  Ryuho Kataoka, National Institute of Polar Research, Japan
  
  ## Citation
  Kataoka, R., S. Nakano, S. Fujita (2023), Machine learning emulator for physics-based prediction of ionospheric response to solar wind variations, submitted to Geophysical Research Letters (submitted in January, 2003)
