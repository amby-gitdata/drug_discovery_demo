# drug discovery demo

this project is based on / ripped off from the dataprofessor youtube channel. all credit attributed to https://www.youtube.com/watch?v=plVLRashaA8 
Data is available on dataprofessor code and data repositories.

## drug_discovery

this code consists of the use of the chembl_webresource_client. we learn how to query a target and find out various molecular species that operate on the target. We can obtain IC50 data. the code also utilizes the rdkit-pypi library and predicts the drug likeness of a compound using Lipinski descriptors. Lastly there are a bunch of visualizations and the mannwhitney test is applied to check if Lipinski descriptors are different between the active and inactive molecules (thresholded based on IC50).

## Acetylcholinesterase_data_analysis

 in this code we use the PaDEL descriptors to train a random forest machine learning algorithm to predict the activity of a molecule against acetylcholinesterase.
