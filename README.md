BasicGPUSkeleton
================

This repository contains skeleton code which lays out the structure of most GPU code for OCT or OCT variants

There will be 4 main external DLL functions:
 1) Allocate memory
 2) Initialize memory
 3) Process frame (CPU->GPU, manipulations, GPU->CPU)
 4) Free memory
