# Multimode Photon Blockade Data
This respository contains the data files and Python code (in the form of a jupyter notebook) used to generate the main figures in "Multimode Photon Blockade" by Chakram, et al. (2022). 

## Required Python Packages
scipy, qutip, numpy, json, pylab, h5py, os, matplotlib, IPython, time, itertools

## Analysis Notebook
The Multimode_Photon_Blockade_Analysis .ipynb file contains the code and analysis required to generate the Figures in the main text. Included are fit functions and classes that perform optimal control pulse simulations and Wigner tomography state reconstruction.

## Data
The individual data files are stored in .h5 format, and can be found in the collected_data folder, with further subfolders for each Figure in the main text. Each .h5 file has stored in it the experiment configuration, hardware device configuration, and quantum device parameters configuration, stored in the "expt_cfg", "hardware_cfg", and "quantum_device_cfg" keys, respectively. The measured data is stored in the "I" key, and experiment sweep parameters, which are different depending on the experiment, can be found in the Multimode_Photon_Blockade_Analysis .ipynb jupyter notebook.

## Contact the Authors
Any inquiries can be directed to the authors of the manuscript, Srivatsan Chakram (schakram@physics.rutgers.edu) and Kevin He (hek@uchicago.edu).