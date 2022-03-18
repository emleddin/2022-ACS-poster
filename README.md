# 2022 ACS Poster

An RMD-based site with additional data for my Spring 2022 ACS poster.

## Requirements
This project uses R 4.1.3 with the shiny and r3dmol packages.

## Orienting Structures
It's easiest to create a new PDB of the atoms you want to show, since users 
are not adding their own representations.
For this project, that means converting the individual XYZs to PDBs and then 
extracting the QM atoms.
After that, orient those PDBs in Chimera to how you want them to be loaded 
initially and saved the transformed coordinates.
Then, remove the connectivity information if it looks incorrect, 
since Jmol will use it!
