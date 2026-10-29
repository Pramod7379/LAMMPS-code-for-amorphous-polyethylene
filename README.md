Details of forcefield can be found in our recent paper:-
*PK Patel, S Basu, "Micromechanical insights into the uniaxial stress-strain behaviour of glassy amorphous polymers through molecular dynamics simulations", 
Journal of the Mechanics and Physics of Solids (2025),  DOI: doi.org/10.1016/j.jmps.2025.106496*  

This repository contains the following files for molecular dynamics simulations of amorphous polyethylene using LAMMPS:
*N_200_single_chain* : A united-atom model of a single polyethylene chain consisting of 200 atoms. 
Users can generate their own single-chain models with different chain lengths, as required for their simulations.

*equilibration.in.in* : A LAMMPS input script describing the equilibration protocol, including NVE and NVT equilibration, NPT equilibration,
and cooling to obtain a glassy polymer sample.

*deformation.in* : A LAMMPS input script for performing uniaxial compression simulations of the polyethylene sample.

These files provide a starting point for constructing, equilibrating, and studying the mechanical response of amorphous polyethylene
using molecular dynamics simulations.
