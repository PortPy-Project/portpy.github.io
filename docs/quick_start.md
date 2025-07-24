## Installation
1. **Using pip**:
   
    * Run the command
      ```
      pip install portpy
      ```
    * You can install optional packages using
      ```
      pip install portpy[mosek, pydicom]
      ```
   * For installing AI related packages
     ```
      pip install portpy[ai]   
     ```
   * For installing all the additional packages
     ```
      pip install portpy[all]   
     ```

2. **From source**:
   
    * Clone this repository using
      ```
      git clone https://github.com/PortPy-Project/PortPy.git
      ```
    * Navigate to the repository with
      ```
      cd portpy
      ```

    * Install the dependencies within a Python virtual environment or Anaconda environment. To set up in a Python virtual environment, install all the dependencies specified in requirements.txt as follows:
        * Create the virtual environment with
          ```
          python3 -m venv venv
          ```
        * Activate the environment with 
          ```
          source venv/bin/activate
          ```
        * Install the requirements using
          ```
          pip install -r requirements.txt
          ```


## Quick Start Guide


The easiest way to start is through the PorPy following Jupiter Notebook examples. 

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