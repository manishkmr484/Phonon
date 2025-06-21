# Phonon DFPT

Commands: mv POSCAR POSCAR-unitcell
mv SPOSCAR to POSCAR

Phonon dispersion:
1. phonopy --fc vasprun.xml
2. phonopy --readfc band.conf -c POSCAR-unitcell

Save band structure in .dat file for manual plotting
3. phonopy-bandplot --gnuplot band.yaml > band.dat


