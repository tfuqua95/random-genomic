# random-genomic

Repository for supplementary data files and scripts to recreate the figures and analyses from Fuqua et al., BioRxiv 2025: https://www.biorxiv.org/content/10.1101/2025.08.25.672121v1

- **Fuqua_2025_source_data.xlsx**: a Microsoft Excel sheet with the raw numbers used to create the panels from the main and supplementary figures. If possible, the file also contains simple graphs and plots for visualization purposes only. To reproduce the actual figures in the main text, see the Jupyter notebook (**Jupyter_notebook_Fuqua_2025.ipynb**).
  
-  **Jupyter_notebook_Fuqua_2025.ipynb**: this virtual notebook contains all of the Python scripts to reproduce the analyses and figures in the manuscript. To run the analyses, we strongly recommend creating a conda environment using the required packages from **environment.yml**. The notebook is organized into sections for each figure (Figures 1-4 and Supplementary Figures 1-12). Before running any cells, you must run all cells under the "Import libraries and functions (run these cells first)" section. This is how the notebook imports functions, packages, and dataframes.
  
-  **pMR1.dna** : This is a map of the pMR1 plasmid. It can be visualized using benchling (https://www.benchling.com/) or other DNA software tools. The libraries were specifically cloned between the EcoRI and BamHI sites in the Mutiple Cloning Site (MCS).
  
-  **Table S1** :  A data frame (Microsoft Excel spreadsheet) containing putative promoter sequences from RegulonDB and their respective matches to the genomic sequences in our dataset.

-  **Data S1**: A data frame (csv format) containing the wild-type random DNA sequences and their respective fluorescence scores.
-  **Data S2**: A data frame (csv format) containing the wild-type genomic DNA sequences and their respective fluorescence scores.
-  **Data S3**: A data frame (csv format) containing the random parent mutagenesis library sequences and their respective fluorescence scores.
-  **Data S4**: A data frame (csv format) containing the genome parent mutagenesis library sequences and their respective fluorescence scores.
-  **Data S5**: a data frame (csv format) containing the associations between gaining or losing transcription factor or sigma factor binding sites and the change this has on fluorescence scores in the random parent sequences.
-  **Data S6**: a data frame (csv format) containing the associations between gaining or losing transcription factor or sigma factor binding sites and the change this has on fluorescence scores in the genome parent sequences.
-  **Data S7**: a data frame (Microsoft Excel spreadsheet) containing primer DNA sequences for polymerase chain reactions (PCRs) and molecular cloning. Available at: https://github.com/tfuqua95/random-genomic.
