# Parallelization-of-PSO
Paralleling  Particle Swarm Optimization using OpenMp, MPI and CUDA frameworks and comparing the performance
Serial PSO: https://github.com/m-ahsen/pso/blob/master/pso_serial.c

  command to run omp.c    : gcc -fopenmp omp.c -lgsl
  command to run mpiomp.c : mpicc -fopenmp mpiomp.c -lgsl
