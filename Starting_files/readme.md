  ### This directory contains the initial .pdb files. ###
  
->The first file: 1z38.pdb was downloaded from pdb.

->Then, with chimera(software), chain A was isolated without ligands.

->Afterwards, with chimera, the file was proceced to Wild Type structure

->Lastly, the mutation was brought to the sequence

[ There was a necessity to "re-write" some residues on the sequence with chimera,
 this was discovered after trying to run a gromacs command (gmx pdb2gmx). gromacs seemed to have problems with some residues,
 for which the structure was incomplete. with chimera the problem was solved and 
 the gmx command could run on both final pdbs ]

On this folder, one can find the initial pdb, the first alterations on chain isolation from chimera and the final, gromacs-ready files.
All the intermediate files from isolated chain to gromacs-ready do not exist because the production of final files was a sequential overwriting on existing files.
