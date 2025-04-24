# Simulation of 2+ Layer Glacier Using TEM Inversion
### Jamie Robson (2025)

This repository outlines the project in which Time Domain Magnetics (TEM) data are used to simulate a 2 layer glacier model. This project is based on data gather from the Taylor Glacier in Antarctica and the subsequent inversion by Blatter et al in 2018. The conductivities and survey set up are taken from this paper, the inversion method is made simpler to make the project doable.

Understanding the movements of glaciers has become of prime importance to scientists under the looming presence of climate change. The total volume of ice on earth is still in debate, some studies estimate that if all ice on earth melted, the sea level would rise by 70 m (NASA , nd) and estimates state that glaciers contain enough water to raise the sea level by approximately 0.5 m (Oerlemans, 2001). Glaciers occur in mountainous regions and are crucial to many communities. During warm periods, ice from these glaciers melts and feeds glacial rivers and lakes. It is also well known that ice in glaciers moves and models of ice flow have been created to model the movements of glaciers in different climate scenarios.  In order to understand these movements, the geometry of the glacier must be understood. This allows for accurate mass balance and models to be created and used in ice flow models of the system.

### Goal
![image](https://github.com/user-attachments/assets/4bc0d632-6f19-4e69-87b0-83d079ddbe95)

Figure 1: (From Blatter et al, 2018). Subglacial conductor model (left) with 150 m of resistive ice and the predicted data (right)

My goal is to recreate this figure and to try to use the inverse method to recover the model and thereby understand the geometry of the glacier.


## Set Up (Updated 2025-04-24)
###### Currently Working Files
- `environment.yml`
    - contains: numpy, matplotlib, simpeg, pandas
- `forward_data.csv`
      - data aquired from the forward model, contains time and magnetic flux data
- `forward_model.ipynb`
      - contains the code to complete the forward modelling and produce a set of data for inversion
- `inverse_model.ipynb` (BUGGY, does not run properly)
      - contains the code to complete the inversion of the data using the data from the forward model

#### Instructions
1. Install environment file `conda env create -f environment.yml`
2. Activate environment file  `conda activate glacier`
3. Download and upload the notebook(s) to your personal Jupyter
4. Run `forwarrd_model.ipynb` then `inverse_model.ipynb`
   
   ** Note: Run all notebooks in the same directory

## Refrences
Blatter et al., 2018, Trans-Dimensional Bayesian Inversion of Airborne Transient EM Data From Taylor Glacier, Antarctica, Geophysical Journal International, 2018, 214,1919–1936.
