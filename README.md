# Maxim Anisimov | HPC & Low-Level Python Specialist

> "Python is just a remote control for LLVM kernels."

### Technical Stack (Strictly Typed & Pre-allocated)
* **Compute:** Numba (@njit), NumPy (Structured Arrays), CUDA (PyCUDA).
* **Optimization:** SIMD (AVX-512/AVX2), L1/L2 Cache Locality, Stride-1 Memory Access.
* **Architecture:** C/Fortran memory layout (Order='C'/'F'), Manual Memory Management.

### Performance Credentials
* 🎓 [Scientific Computing with Python (freeCodeCamp)]([https://freecodecamp.org](https://freecodecamp.org/certification/maximanisimov/python-v9))
* 🚀 Focus: Eliminating Python Object Overhead in Data Pipelines.

### System Principles:
1. **NO** dynamic lists or dicts in hot loops.
2. **NO** `append()` calls. Buffers are pre-allocated at `t=0`.
3. **ONLY** Numba-compiled functions for critical paths.
