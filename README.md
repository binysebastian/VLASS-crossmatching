# VLASS-crossmatching



<!-- ABOUT THE PROJECT -->
## About The Project

This project identifies the sources from the input image file using PyBDSF. It then crossmatches between the sources identified from the input image file and the VLASS Quick Look source catalog. It writes out a table of source flux densities, and spectral index values estimated at the location of the source regions present in the VLASS Quick Look catalog. In addition, it prints the position and flux densities of the sources which were undetected in the single epoch images. It also displays the single epoch image region and the flux density estimated crudely around the undetected source for further analysis.




<!-- GETTING STARTED -->
## Getting Started
To be able to run the code on your local machine make sure you have the following prerequisites, a copy of the code and the inputs files.

### Prerequisites

This python code is dependant on few astronomy python packages.
* [bdsf](https://www.astron.nl/citt/pybdsf/)
* [astropy](https://www.astropy.org/)
* [casatasks](https://casadocs.readthedocs.io/en/stable/notebooks/usingcasa.html#Modular-Installation-of-CASA-6) (optional)
  

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/binysebastian/VLASS-image-crossmatching
   ```

<!-- USAGE EXAMPLES -->
## Inputs

The code requires the following user inputs.
* A quick look catalog of sources (eg: [CIRADA Quick Look catalogue](https://www.cadc-ccda.hia-iha.nrc-cnrc.gc.ca/files/vault/cirada/continuum/VLASS_QL_comp_catalogues_yg/VLASS1QLCIR_v1/CIRADA_VLASS1QL_table2_hosts.csv.gz)).
* Two Single Epoch image file names (for the tt0 and tt1 images) ([see here for 4 sets of sample images](https://ws.cadc-ccda.hia-iha.nrc-cnrc.gc.ca/files/vault/cirada/catalogues/github_files/testdata.tar)).


## Outputs





<!-- CONTACT -->
## Contact

Biny Sebastian - binysebastian@gmail.com

Project Link: [https://github.com/binysebastian/VLASS-image-crossmatching](https://github.com/binysebastian/VLASS-image-crossmatching)



