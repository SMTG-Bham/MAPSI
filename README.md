# MAPSI

Repository for paper: (CH<sub>3</sub>NH<sub>3</sub>)<sub>2</sub>Pb(SCN)<sub>2</sub>I<sub>2</sub>: A More Stable Structural Motif for Hybrid Halide Photovoltaics?

DOI:[10.1021/acs.jpclett.5b02177](http://pubs.acs.org/doi/10.1021/acs.jpclett.5b02177)

Optimised crystal structures of MAPSI from density functional theory, calculated using the Vienna *Ab initio* Package (VASP).

Computational Details
-----------------------
The crystal structure of MAPSI obtained by Daub and Harald Hillebrecht was used as the starting point for the calculations.<sup>1</sup>

We have optimised the structures using 3 different functionals: PBEsol, PBEsol + Grimme’s D3 dispersion correction (PBEsol+D3), and PBE+D3.
The final structures have been obtained following an iterative procedure where the ion positions, cell shape, and cell volume are allowed to change (`ISIF = 3` in VASP) using a Quasi-Newton algorithm.

Requirements
------
To open the .cif file, a viewer such as [VESTA](http://jp-minerals.org/vesta/en/).
To run the `POSCAR` file: a VASP license, and suitable input `INCAR`, `KPOINTS`, and `POTCAR` files.

Disclaimer
------
This file is not affiliated with VASP. Feel free to use and modify, but do so at your own risk.

References
-------
1. M. Daub and H. Hillebrecht, Synthesis, Single-Crystal Structure and Characterization of (CH<sub>3</sub>NH<sub>3</sub>)<sub>2</sub>Pb(SCN)<sub>2</sub>I<sub>2</sub>, *Angewandte Chemie*, **54**, 11168-11169 (2015) doi: [10.1002/anie.201506449](http://onlinelibrary.wiley.com/doi/10.1002/anie.201506449/abstract)
