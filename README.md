# modulome_sc_2025
iModulon structure for _Saccharomyces cerevisiae_.

Structure of this github:

notebooks: contains python notebooks containing pymodulon code for analysis and and characterization of the iModulons

data: storage of data relevant to analysis including external annotations, generated structures, and other relevant information. The data folder is attached in .zip format to the releases for this repository.

## Environment Creation
Using conda, install environoment with the following command: conda env create -f environment.yml

For the quality control notebooks (1a and 1b) an additional environment is necessary: conda env create -f qc_environment.yml

## Data
Data necessary for use (including test data) is included as a zip file under releases for this repository. Unzip the file to a folder 'data' under the repository root. In the attached zipped folder, there is also a json file of the iModulon structure for _S. cerevisiae_.
