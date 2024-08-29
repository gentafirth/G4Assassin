# G4Assassin
JupyterNotebook to perform handsfree G4Hunter analysis on libraries of genomes. Original G4Hunter software is https://github.com/AnimaTardeb/G4Hunter

# Required libraries
- BioPython
- Matplotlib
- Numpy
- Pandas
- os
- subprocess
- glob

# Instructions
1. Rename GENOMES variable as the file path to your library of genomes. This will search all subfolders of varying depths, and save all directories of every FASTA files within the directory
```
# For example
GENOME = 'Genomes/'
# This is the filepath to a folder within the same folder as G4Assassin.ipynb
```
