# Phonon DFPT

Commands:
1. mv POSCAR POSCAR-unitcell
2. mv SPOSCAR to POSCAR

Phonon dispersion:
1. phonopy --fc vasprun.xml
2. phonopy --readfc band.conf -c POSCAR-unitcell

Save band structure in .dat file for manual plotting
1. phonopy-bandplot --gnuplot band.yaml > band.dat

Save phonon band + DOS
1. phonopy --readfc pdos.conf -p -s -c POSCAR-unitcell [here -p to plot, -s to save, -c to read POSCAR-unitcell]


