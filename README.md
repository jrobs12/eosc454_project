# Simulation of 2+ Layer Glacier Using TEM Inversion
### Jamie Robson (2025)

This repository outlines the project in which Time Domain Magnetics (TEM) data are used to simulate a 2 layer glacier model. This project is based on data gather from the Taylor Glacier in Antarctica and the subsequent inversion by Blatter et al in 2018. The conductivities and survey set up are taken from this paper, the inversion method is made simpler to make the project doable.

### Goal
![image](https://github.com/user-attachments/assets/4bc0d632-6f19-4e69-87b0-83d079ddbe95)

Figure 1: (From Blatter et al, 2018). Subglacial conductor model (left) with 150 m of resistive ice and the predicted data (right)

## Set Up (Updated 2025-03-24)
###### Currently Working Files
- environment.yml
    - contains: numpy, matplotlib, simpeg
- Notebooks to complete the forwad simulation are provided as well (forward_simulation.ipynb)
###### Future Notebooks
- python file with function to make model and predict data
- notebook to complete inversion

#### Instructions
1. Install environment file `conda env create -f environment.yml`
2. Activate environment file  `conda activate glacier`
3. Download and upload the notebook(s) to your personal Jupyter
   
   ** Note: Run all notebooks in the same directory

## Refrences
Blatter et al., 2018, Trans-Dimensional Bayesian Inversion of Airborne Transient EM Data From Taylor Glacier, Antarctica, Geophysical Journal International, 2018, 214,1919–1936.
