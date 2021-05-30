# hpc_lecture

- 学籍番号: 21M30867
- 氏名: Zhang Xinyu

Final report:
`/16_final_report/matmul.cpp`

コンパイル・実行コマンド: \
`mpicxx matmul.cpp -O3 -fopenmp -march=native` \
`mpirun -np 4 ./a.out`

OpenMP・SIMD・キャッシュブロッキングを加えた．

ログインノード上で実行したときの出力の例:
```
N    : 1024
comp : 0.007275 s
comm : 0.008975 s
total: 0.016250 s (132.156117 GFlops)
error: 0.000102
```


|          | Topic                                | Sample code               |
| -------- | ------------------------------------ | ------------------------- |
| Class 1  | Introduction to parallel programming |                           |
| Class 2  | Shared memory parallelization        | 02_openmp                 |
| Class 3  | Distributed memory parallelization   | 03_mpi                    |
| Class 4  | SIMD parallelization                 | 04_simd                   |
| Class 5  | GPU programming 1                    | 05_openacc                |
| Class 6  | GPU programming 2                    | 06_cuda                   |
| Class 7  | Parallel programing models           | 07_starpu                 |
| Class 8  | Cache blocking                       | 08_cache_cpu,08_cache_gpu |
| Class 9  | High Performance Python              | 09_python                 |
| Class 10 | I/O libraries                        | 10_io                     |
| Class 11 | Parallel debugger                    | 11_debugger               |
| Class 12 | Parallel profiler                    | 12_profiler               |
| Class 13 | Containers                           |                           |
| Class 14 | Scientific computing                 | 14_pde                    |
| Class 15 | Deep Learning                        | 15_dl                     |
