# lecture1

Example files for the multiplication of the components of two vectors,
and the computation of the inner product between two vectors.
Contains serial version, as well as OpenMP and MPI versions.

For the OpenMP example, you need to use a somewhat recent compiler,
and must use -fopenmp to link against the OpenMP libs, e.g.:

gcc inner-omp.c -a inner-omp -fopenmp

You might have to include the library flag -lrt for openmp compiles



