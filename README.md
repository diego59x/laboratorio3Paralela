# Laboratorio 3: Vectores y MPI

Objetivo: implementar y diseñar programas mediante intercambio de mensajes y memoria distribuida usando MPI.

## Instrucciones para compilar programas

 - vector_add en mac: gcc-12 -g -Wall -o vector_add vector_add.c -fopenmp
 - mpi_vector_add en mac: mpicc -o mpi_vector_add mpi_vector_add.c

## Instrucciones para correr programas

 - vector_add: ./vector_add
 - mpi_vector_add en mac: mpirun -np 4 ./mpi_vector_add 