# Rewriting a Deep Generative Model

This is the source code release for the paper
[**Rewriting a Deep Generative Model**](https://rewriting.csail.mit.edu/).

[![Video](/setup/video-thumbnail.png)](https://rewriting.csail.mit.edu/video/) 

The code runs using pytorch.

* The method and interface can be found in `/rewriting`
* Notebooks are in `/notebooks`: see `rewriting-interface.ipynb` for the demonstration UI.
* Quantitative experiments in `/metrics`, dissection utilities in `/utils`.

## Setup

It's designed to use a recent version of pytorch (1.4+) on python (3.6), using
cuda 10.1 and cudnn 7.6.0.  The `/setup` directory has a script to create a
conda environment that should work.

