# Phonon DFPT

Commands: mv POSCAR POSCAR-unitcell
mv SPOSCAR to POSCAR

Phonon dispersion:
1. phonopy --fc vasprun.xml
2. phonopy --readfc band.conf -c POSCAR-unitcell
