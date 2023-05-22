# REPPU-ESN
The machine-learning based surrogate model for the ionospheric outputs from REPPU global MHD simulation is developed using the echo state network (ESN, e.g., [Tanaka et al., Phys. Rev. Res. 2022](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.4.L032014)). The python codes and the training dataset for the ESN-based emulator model (Kataoka et al., 2023, submitted to GRL) are provided here.

  ## Files
  * bigsig756n.dat: REPPU simulation results of height-integrated conductivity. 
  * bigfac756n.dat: REPPU simulation results of field-aligned current. 
  * bigpot756n.dat: REPPU simulation results of ionospheric potential. 
  * sw756.txt: Solar wind input data. 
  * rep_emu.ipyb: Jupyter notebook demo, for reproducing Figure 3 in the reference paper.
  * synth_clock180.txt: Synthetic solar wind input data. 

  ## How to Use
  * Run the sample code rep_emu.ipyb in the jupyter notebook.
  * Some python modules, such as numpy, scipy, matplotlib, and networkx, as well as [esn_dts_openloop.py](https://github.com/GTANAKA-LAB/DTS-ES), are required to run the codes. 

  ## Developer
  Ryuho Kataoka, National Institute of Polar Research, Japan
  
  ## Citation
  Kataoka, R., S. Nakano, and S. Fujita (2023), Machine learning emulator for physics-based prediction of ionospheric response to solar wind variations, submitted to Geophysical Research Letters (submitted in January, 2003)
  Preprint: Ryuho Kataoka, Shinya Nakano, Shigeru Fujita. Machine learning emulator for physics-based prediction of ionospheric response to solar wind variations. ESS Open Archive . January 17, 2023.
  DOI: 10.22541/essoar.167397423.39654060/v1
