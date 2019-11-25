# Dataset and scripts to build machine learning models for the classification of the bitter and sweet taste of small molecules

This is an example/portfolio project in which using a publicly available real-life dataset, I have demonstrated different aspects of data science/machine learning. The dataset is based on the study from Cosy lab (https://github.com/cosylabiiit/bittersweet) on classifying small molecules into bitter and sweet classes. From the original project, I have only borrowed the list of the molecules with their SMILES and target labels. I have converted the SMILES into their canonical forms using RDKit and then used Mordred (https://github.com/mordred-descriptor)  to calculate molecular descriptors (features). My intention in this project is to demonstrate steps all the way from feature generation/selection to modeling. A more elaborate discussion on the methods used is documented within the Jupyter notebooks along with the code. Steps involving feature generation require some domain knowledge of computational chemistry; however, the rest of the project can be viewed as any generic data science project.

## Singularity Container
For reproducibility please use the latest singularity container hosted at: [https://cloud.sylabs.io/library/_container/5ddc495c54b1ada33dabbed7](https://cloud.sylabs.io/library/_container/5ddc495c54b1ada33dabbed7)

**Files in the data folder.**  
1. **bitter, sweet - [test, train].tsv:** Original files from https://github.com/cosylabiiit/bittersweet
2. **df_canon_smiles.pkl:** Pandas pickle with canonical SMILES for each parsable SMILES string.  
3. **bitter_sweet_2d_descriptors.[pkl, tsv].gz:** Pandas pickle and TSV files with  2D descriptors for each parsable SMILES string.  
4. **bitter_sweet_2d_plus_3d_descriptors.[pkl, tsv].gz:** Pandas pickle and TSV files with 2D and 3D descriptors for each parsable SMILES string.  
