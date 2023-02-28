# Connectomes workshop

## Set up workshop materials:

Clone the repository and change the working directory into the root directory
of the repository:
```sh
git clone https://github.com/juaml/crc_workshop_connectomes.git
cd crc_workshop_connectomes
```
Within the repository, there is a submodule called `aomic-fc`, [which is a datalad
dataset that contains the preprocessed connectomes](https://gin.g-node.org/LeSasse/aomic-fc).
Since it is a submodule, from the root directory you can get the necessary data
by running:
```sh
datalad get aomic-fc/junifer_storage/JUNIFER_AOMIC_TSV_CONNECTOMES/ID1000/ID1000_BOLD_parccortical-Schaefer100x17FSLMNI_parcsubcortical-TianxS2x3TxMNInonlinear2009cAsym_marker-empiricalFC_moviewatching.tsv
```