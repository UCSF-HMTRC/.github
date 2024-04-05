# Hyperpolarized MRI Technology Resource Center

The goal of this organization is to provide a centralized respoistory of tools for hyperpolarized MRI experiments.  It is supported by the Hyperpolarized MRI Technology Resource Center (HMTRC), housed at the Uniersity of California - San Francisco (UCSF) and funded by the US NIH National Institute of Biomedical Imaging and Bioengineering (NIBIB) grant # NIH P41EB013598.

The content includes simulations, digital phantoms, pulse sequence development software, pulse sequence programs, image reconstruction, data processing, and data analysis.
See https://hyperpolarizedmri.ucsf.edu/research-tools-dissemination for more information

## Major Projects

### hyperpolarized-mri-toolbox

https://github.com/LarsonLab/hyperpolarized-mri-toolbox

The goal of this toolbox is to provide research-level and prototyping software tools for hyperpolarized MRI experiments. It is currently based on Matlab code, and includes code for designing radiofrequency (RF) pulses, readout gradients, and data reconstruction.

###  Spectroscopic Imaging VIsualization and Computing (SIVIC)

https://github.com/SIVICLab/sivic

The goal of this package is to provide data processing and visualization tools for MR spectroscopic imaging, include hyperpolarized MRI data.  It includes command line tools for data processing and a powerful GUI to navigate and visualize data.

## Private Pulse Sequence Programs

This organization also hosts pulse sequence programs for MRI scanners from Bruker, and GE Healthcare.  
These repositories are available by request because they rely on proprietary components, please email hyperpolarizedmri@ucsf.edu for access requests

Current methods include
* Bruker Slab Spectroscopy
* Bruker 2D CSI
* Bruker 2D EPSI
* GE Metabolic-specific imaging with EPI
* RTHawk Resesarch metabolite-specific imaging with spirals and real-time calibration methods

## Pulseq Pulse Sequence Programs

The Pulseq project is an open source framework for the development and execution of magnetic resonance (MR) pulse sequences for imaging and spectroscopy, and recently there are several available methods for Hyperpolarized MRI:

* X-EPI - echo-planar imaging (EPI) sequences for X-nuclei, including spectral-spatial RF Excitation. 
https://x-epi.readthedocs.io/en/latest/
* Metabolite-specific bSSFP, gradient-echo spiral methods
https://github.com/Xiaoxi-Liu/C13_sequences_Pulseq
* Multi-echo bSSFP
https://github.com/ZirunWang666/Pulseq_me_bssfp
