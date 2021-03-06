# Δoxa Binarization Framework - Python

## Introduction
This is an **experimental** project that exposes the ΔBF, written in C++, to Python via Pybind11.  For a simple example of how it works, checkout the [Python](../../Demo/Python) demo.

## Building with Pybind11
Release Build
```
git submodule update --init --recursive
cd Bindings\Python
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

## License
CC0 - Brandon M. Petty, 2021

To the extent possible under law, the author(s) have dedicated all copyright and related and neighboring rights to this software to the public domain worldwide. This software is distributed without any warranty.

[View Online](https://creativecommons.org/publicdomain/zero/1.0/legalcode)

"*Freely you have received; freely give.*" - Matt 10:8