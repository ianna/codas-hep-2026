# CoDaS-HEP-2026: The Scientific Python Ecosystem

Python has become the dominant programming language for scientific computing, combining an accessible high-level interface with high-performance compiled libraries. Although Python itself is interpreted, much of the scientific ecosystem is built on optimized C, C++, and CUDA implementations, enabling researchers to write expressive code while achieving near-native performance.

This tutorial introduces the modern Scientific Python ecosystem for data analysis and high-performance computing. We begin with the fundamentals of NumPy, SciPy, Matplotlib, and JIT compilation using Numba, before exploring GPU programming with CuPy and cuda.compute, including parallel algorithms, iterators, and GPU execution patterns.

The second half of the tutorial focuses on the Scikit-HEP ecosystem for high-energy physics. Participants will learn how to read ROOT data with Uproot, analyze irregular event data using Awkward Array, perform jet clustering with FastJet, fit models with iminuit, and carry out statistical inference with pyhf. Throughout the tutorial, we emphasize vectorized programming, composable array operations, and scalable analysis workflows that run efficiently on both CPUs and GPUs.

## Getting Started

1. Start your binder:

https://binderhub.ssl-hep.org/v2/gh/codas-hep-2026/images/columnar-analysis?gpuModel=&gpuCount=1&cudaMajor=undefined&cudaMinor=undefined&site=nrp&memory=4.0&cpu=1&qos=Guaranteed

2. Clone this repo in the binder terminal:
```bash
git clone https://github.com/ianna/codas-hep-2026
```
3. Follow the notebooks which are in the `scientific-python` folder.
