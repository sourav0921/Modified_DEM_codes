# Modified_DEM_codes

**Steps to run the modified LAMMPS code**
1. Download the LAMMPS source file from "https://www.lammps.org/download.html"
2. The current modification is tested for LAMMPS stable version "23 Jun 2022"
3. The modified code for contact model can be implemented through first copying the ***src*** folder to the original ***src*** folder of the LAMMPS directory and then compile the software with running the following command in linux terminal 
4. make yes-GRANULAR
5. make mpi

**Steps to run the modified LIGGGHTS code**
1. Download the LIGGGHTS source code from https://github.com/CFDEMproject/LIGGGHTS-PUBLIC
2. The modified code for the contact model can be implemented through first copying the ***src*** folder to the original LIGGGHTS-PUBLIC directory and then compile the software with running the following command in linux terminal
3. make auto
