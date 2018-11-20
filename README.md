# Dataset to build machine learning models for the classification of the bitter and sweet taste of small molecules

Based on https://github.com/cosylabiiit/bittersweet

RDKit and Mordred (https://github.com/mordred-descriptor)  were used to calculate Canonical SMILES and descriptors (features) respectively.

**Files in the data folder.**  
1. **bitter, sweet - [test, train].tsv:** Original files from https://github.com/cosylabiiit/bittersweet
2. **df_canon_smiles.pkl:** Pandas pickle with canonical SMILES for each parsable SMILES string.  
3. **bitter_sweet_2d_descriptors.[pkl, tsv].gz:** Pandas pickle and TSV files with  2D descriptors for each parsable SMILES string.  
4. **bitter_sweet_2d_plus_3d_descriptors.[pkl, tsv].gz:** Pandas pickle and TSV files with 2D and 3D descriptors for each parsable SMILES string.  
