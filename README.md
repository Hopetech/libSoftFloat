---
# libSoftFloat
---


## About

Implementation of a library of double precision operations in pure GLSL 1.30 for GPU using bit twiddling operations and integer math.

This library is the translation of SoftFloat by John R. Hauser in GLSL in order to address GPUs instead of CPUs.


## Goals

* The first goal is to be able to compute FP64 on GPUs without FP64 hardware support.

* A streach goal of this project is to integrate it into [Mesa](https://www.mesa3d.org) and create GL\_ARB\_gpu\_shader\_fp64.

For more details, see [my presentation](https://github.com/Hopetech/XDC2016) at XDC'16, [my website](https://hopetech.github.io/) or simply [email me](#author).


## GSoC

This project began with the [Google Summer of Code](https://developers.google.com/open-source/gsoc/) 2016.


## Author

Elie Tournier

tournier.elie@gmail.com

https://github.com/Hopetech
