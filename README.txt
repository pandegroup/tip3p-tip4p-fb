This repository contains files for running simulations using the
TIP3P-FB and TIP4P-FB water models in Gromacs, OpenMM and AMBER. 

For OpenMM we provide:
- PDB coordinates for 512-water box
- Force field XML file
- Run configuration file
- OpenMM-MD.py script for running simulation

For Gromacs we provide:
- Coordinate .gro file for 512-water box
- Topology .top file for 512-water box
- Parameter .itp file
- Run configuration file

For AMBER we provide:
- Force field .frcmod parameter file
- solvents.cmd for generating solvents .lib file in AMBER distribution
- fb4box.off and fb3box.off coordinates for use with tleap
