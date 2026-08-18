Replicate the unit cell relaxed by VASP by replicate command in in_file;
Then create voids by the commend after the replicate command in in_file;
Set the potential parameters which correspond to the correct atom type in in_file;
Adjust the charge of the system to charge neutral;
Relax the structure until energy is stable;
Check the structure after relaxation;
Run MSD curve to generate the diffusivity;
The log, log.lammps, msd, and nvt.lammpstrj files are the results for the 20%+6-grain polycrystalline structure for diffusivity at 700 K.
The in_file and initial_structure_relaxed_by_VASP could help people build voids in single crystalline and polycrystalline;
The polycrystalline structure could be built by nitial_structure_relaxed_by_VASP with ATOMSK software.
