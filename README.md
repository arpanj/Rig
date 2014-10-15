Rig
===

Reference and Optimized implementations of Rig, A simple, secure and flexible design for Password Hashing

The reference code should compile cleanly on windows and unix.

The optimized implementation is written using AVX-2 and would need a CPU (Ex. 4th Gen Intel Core).
The optimized code provides a speedup of 1.5 times or more.

See: https://github.com/arpanj/Rig/blob/master/Rig_v2-opt/main.c for benchmark results.

See note on 'https://github.com/arpanj/Rig/blob/master/Rig_v2-ref/rig.h' for information to switch between the two variants of the Rig construction.

