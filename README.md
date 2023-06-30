# GPU-Acclerated Single Cell Analysis 
Applying the Nvidia RAPIDS-accelerated single-cell data analysis pipeline on Genome-Explorer. 

### Machine Specs: 
 1. AMD Ryzen Threadripper Pro 5995X 64 Cores 128 Threads
 2. 512GB DDR4-ECC RAM
 3. Nvidia RTX A6000 48GB 

### Current Environments
 1. scGPU: for use with RAPIDS-accelerated Scanpy
 2. scGPU-scANVI: for use with RAPIDS-accelerated Scanpy and GPU-enabled scvi-tools (including scANVI)

### Notebooks and Scripts:
 1. 70,000 human lung cells GPU and CPU notebooks (Nvidia examples)
 2. 500,000 mouse brain 10X GPU and CPU notebooks (modified Nvidia examples)
 3. Functions file: rapids_scanpy_funcs.py - minor tweaks to work with updated RAPIDS
