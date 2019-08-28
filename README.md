# bssopenffhack
Exploring interoperability of BioSimSpace and OpenFF toolkits


Goal 1) Testing OpenFF --> BSS flows
- parameterise a molecule with OpenFF/SMIRNOFF. Then solvate with BSS and run a BSS MD with SOMD, Gromacs or NAMD. 
- same as above but setting up FEP inputs

Goal 2) Testing BSS --> OpenFF flows
- load a solvated and parameterised system with BSS, pass the data to OpenFF, reparameterise components and save output in a format that can be read back into BSS. 
