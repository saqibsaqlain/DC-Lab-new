
    openmp programs compilation
    gcc -fopenmp filename.c
    
    To compile program 3
    gcc -fopenmp -lm 3.c
    
    To compile and execute program 6
    gcc -fopenmp 6.c -lgd
    ./a.out input.png output.png #processes
    
    MPI program compilation and execution
    mpicc filename.c
    mpirun -np #noofprocesses ./a.out
