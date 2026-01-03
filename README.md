# AMBER_ligand_topology_creation
Installing and setting up AMBER forcefield for Ligand parameterization and topology creation

## Installing AMBERTOOLS and ACPYPE

### 1) Update Ubuntu environment

    sudo apt update && sudo apt upgrade -y

### 2) Download & Install Anaconda/Miniconda

### 3) Setting up conda environment for AmberTools

#### a) Check the available versions of AmberTools

#### b) Create environment:
    conda create --name AmberTools24
    conda activate AmberTools24
    
    conda list ambertools 
    pip install acpype

### 3) Running AmberTools for a neutral compound

    acpype -i lig_converted.mol2 -c bcc -n 0
