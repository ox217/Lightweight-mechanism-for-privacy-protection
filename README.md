# Lightweight-mechanism-for-privacy-protection
The codes in this repository correspond to those used in the paper React to the Worst: Lightweight and proactive protection of location privacy of Emilio Molina, Mirko Fiacchini, Sophie Cerf, and Bogdan Robu.

## Running 

The simulation and analysis uses Python version 3.8 or later. The modules used in this method are listed in the pip-format file `requirements.txt`.

To install them use:
`$ pip install -r requirements.txt`


The offline stage is performed in `OfflineV2.ipynb`, then in `postProcessing_offline.ipynb` the function $f_D$ is calculated. This function is needed to run the online stage in `OnlineV2.ipynb`.
