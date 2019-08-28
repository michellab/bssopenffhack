# bssopenffhack
Exploring interoperability of BioSimSpace and OpenFF toolkits


Experiment 1) OpenFF --> BSS flow
- parameterise ethane molecule with OpenFF/SMIRNOFF. Then solvate with BSS and run a BSS MD with SOMD or Gromacs. 
  --> See Prototyping.ipynb 
  
Experiment 2) OpenFF --> BSS flow
- parameterise ethane with OpenFF
- parameterise methanol with OpenFF
- generate merge molecule with BSS
- create FEP inputs for SOMD or Gromacs

Experiment 3)  BSS --> OpenFF flow
- load an ethane.prm7 molecule in BSS 
- get the molecule and parameterise with OpenFF 
