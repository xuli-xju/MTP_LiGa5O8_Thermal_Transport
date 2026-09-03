# Data for Defect-dependent Thermal Transport in LiGa5O8

This repository contains the main simulation files used in the study:

## Structure

### `structure/POSCAR_LiGa5O8_relaxed`

Relaxed primitive-cell structure of pristine LiGa5O8 used as the reference structure for subsequent calculations.

**Defect-dependent thermal transport in LiGa5O8: A machine-learning interatomic potential study**

The data include force constants used in Boltzmann transport equation (BTE) calculations and input files for molecular dynamics (MD) simulations based on the trained moment tensor potential (MTP).

## Directory structure

```text
data/
├── bte/
│   ├── dft/
│   │   ├── FORCE_CONSTANTS_2ND
│   │   └── FORCE_CONSTANTS_3RD
│   └── mtp/
│       ├── FORCE_CONSTANTS_2ND
│       └── FORCE_CONSTANTS_3RD
└── md/
    ├── 484.data
    ├── in
    └── pot.almtp
