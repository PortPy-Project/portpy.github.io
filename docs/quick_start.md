## Installation
???+ example "Installing PortPy"

    === "pip/conda"

        To install PortPy with all its dependecies (recommonded).
        ```bash
        pip install portpy[all]
        ```
        To install PortPy with only optional dependencies.
        ```bash
        pip install portpy[ai, mosek, pydicom]
        ```
        To install PortPy with only the core dependencies.
        ```bash
        pip install portpy
        ```

    === "From source"

        1- Clone this repository 
        ```bash
        git clone https://github.com/PortPy-Project/PortPy.git
        ```
        2- Navigate to the repository 
        ```bash
        cd portpy
        ``` 
        3- Install the dependencies within a Python/Anaconda virtual environment 
              ```bash
              pip install -r requirements.txt
              ```        

## Quick Start Guide


The easiest way to start is through the PorPy following Jupiter Notebook examples:

| Example File                          	                                                                                                                          | Description                                                                                                                                                           	                                                                          |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [1_basic_tutorial.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/1_basic_tutorial.ipynb)                	                                  | Demonstrates the main functionalities of PortPy (e.g., Access data, create an IMRT plan, visualize)                                                                   	                                                                          |
| [eclipse_photon_dose_calculation.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/eclipse_photon_dose_calculation.ipynb)                	 | Demonstrates the capability of running dose calculation for patients outside PortPy dataset using Varian's photon dose calculation module and perform optimization in PortPy                                                                   	 |
| [vmat_scp_tutorial.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/vmat_scp_tutorial.ipynb)               	                                 | Creates a VMAT plan using sequential convex programming                                                                                                               	                                                                          |
| [vmat_scp_dose_prediction.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/vmat_scp_dose_prediction.ipynb)                                   | Predicts 3D dose distribution using deep learning and converts it into a deliverable VMAT plan                                                                        	                                                                          |
| [3d_slicer_integration.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/3d_slicer_integration.ipynb)           	                             | Creates an IMRT plan and visualizes it in 3D-Slicer                                                                                                                   	                                                                          |
| [imrt_tps_import.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/imrt_tps_import.ipynb)                	                                    | 1. Outputs IMRT plan in DICOM RT format and imports it into TPS. <br>2. Outputs IMRT plan optimal fluence in an Eclipse-compatable format and imports it into Eclipse 	                                                                          |
| [vmat_tps_import.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/vmat_tps_import.ipynb)                 	                                   | Outputs VMAT plan in DICOM RT format and imports it into TPS                                                                                                          	                                                                          |
| [imrt_dose_prediction.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/imrt_dose_prediction.ipynb)            	                              | Predicts 3D dose distribution using deep learning and converts it into a deliverable IMRT plan                                                                        	                                                                          |
| [vmat_global_optimal.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/vmat_global_optimal.ipynb)           	                                 | Finds a globally optimal VMAT plan                                                                                                                                    	                                                                          |
| [beam_orientation_global_optimal.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/beam_orientation_global_optimal.ipynb) 	                   | Finds globally optimal beam angles for IMRT                                                                                                                           	                                                                          |
| [dvh_constraint_global_optimal.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/dvh_constraint_global_optimal.ipynb)  	                      | Finds a globally optimal plan meeting Dose Volume Histogram (DVH) constraints                                                                                         	                                                                          |
