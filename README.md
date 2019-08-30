# bssopenffhack
Exploring interoperability of BioSimSpace and OpenFF toolkits


Experiment 1) OpenFF --> BSS flow
- parameterise ethane molecule with OpenFF/SMIRNOFF. Then solvate with BSS and run a BSS MD with SOMD or Gromacs. 
  --> See smirnoff_to_BSS.ipynb 

Experiment 2)  BSS --> OpenFF flow
- load an ethane.prm7 molecule in BSS 
- get the molecule and parameterise with OpenFF 
 
Experiment 3) OpenFF --> BSS flow (not done)
- parameterise ethane with OpenFF
- parameterise methanol with OpenFF
- generate merge molecule with BSS
- create FEP inputs for SOMD or Gromacs

Meeting notes
https://docs.google.com/document/d/18B87lB9pv8AGm0fcPCgmHTUjT1L9G-l_3ujz3clKBUA/edit#heading=h.g2xkwe239ej9
