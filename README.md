# MCEND basis set library

This is the library that contains the [MCEND]() basis sets. The basis sets were generated using [Psi4] and Python scripts as included in the [MCEND-tools]() repository.

Since MCEND is an electron-nuclead dynamics package, the basis sets that are used contain electronic and nuclear degrees of freedom. They are therefore no electronic, but electron-nuclear basis sets, specific to the kind of molecule. 

The nuclear basis is further set up on an interpolated grid using the information in the basis set library.

For any changes to the settings of nuclear or electronic basis, you need to generate a new basis set (or select one from the library).

## Contents
At the moment, the basis set library contains the following basis sets. The number of remaining electronic basis functions is a result of the numerical threshold that was set to exclude numerically dependent orbitals. The overlap of the orbitals is found in the file `smateigvals.n`, from where the threshold can be deduced. The nuclear grid points and information about the basis set can be found in the `rsp_MOLECULE` and `info-MOLECULE.dat` files.

### H<sub>2</sub><sup>+</sup>

| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 4 | cc-pVDZ | 17 | integrals_H2-1-2-bf17 |

### H<sub>2</sub>

| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 6 | STO-3G | 12 | integrals_H2-bf12 |
| 4 | STO-3G | 8 | integrals_H2-bf8 |
| 4 | cc-pVDZ | 17 | integrals_H2-g4bf17 |
| 4 | aug-cc-pVDZ | 27 | integrals_H2-g4bf27 |
| 4 | aug-cc-pVDZ | 29 | integrals_H2-g4bf29 |
| 4 | cc-pVTZ | 49 | integrals_H2-g4bf49 |
| 4 | aug-cc-pVTZ | 66 | integrals_H2-g4bf66 |
| 4 | aug-cc-pVTZ | 70 | integrals_H2-g4bf70 |
| 6 | cc-pVDZ | 31 | integrals_H2-g6bf31 |
| 6 | aug-cc-pVDZ | 43 | integrals_H2-g6bf43 |

**A further basis set, integrals_H2-g6bf107, was excluded because of the size.**

### HeH<sup>+</sup>

| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 4 | cc-pVDZ | 16 | integrals_HeH+-bf16 |
| 4 | aug-cc-pVDZ | 24 | integrals_HeH+-bf24 |
| 4 | cc-pVTZ | 44 | integrals_HeH+-bf24 |
| 4 | aug-cc-pVTZ | 60 | integrals_HeH+-bf60 |

### He<sub>2</sub>

| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 4 | cc-pVDZ | 16 | integrals_He2-bf16 |
| 4 | aug-cc-pVDZ | 24 | integrals_He2-bf24 |

### BeH<sup>+</sup> 

| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 4 | cc-pVDZ | 29 | integrals_BeH+-bf29 |
| 4 | cc-pVDZ | 29 | integrals_BeH+-bf29v1a |
| 4 | cc-pVDZ | 29 | integrals_BeH+-bf29v1b |
| 4 | cc-pVDZ | 29 | integrals_BeH+-bf29v1c |
| 4 | cc-pVDZ | 29 | integrals_BeH+-bf29v2 |
| 4 | cc-pVDZ | 29 | integrals_BeH+-bf29v3 |
| 4 | cc-pVDZ | 29 | integrals_BeH+-bf29v5 |
| 4 | cc-pVDZ | 30 | integrals_BeH+-bf30 |
| 4 | cc-pVDZ | 30 | integrals_BeH+-bf30v4 |
| 4 | cc-pVDZ | 31 | integrals_BeH+-bf31 |
| 4 | cc-pVDZ | 31 | integrals_BeH+-bf31v0 |
| 4 | cc-pVDZ | 31 | integrals_BeH+-bf31v0b |
| 4 | cc-pCVDZ | 37 | integrals_BeH+-bf37v4 |
| 4 | cc-pCVDZ | 38 | integrals_BeH+-bf38 |

### B<sub>2</sub>

| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 4 | cc-pVDZ | 55 | integrals_B2-0-3-bf55 |

### LiH

| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 4 | cc-pVDZ | 40 | integrals_LiH-0-1-bf40 |
| 4 | STO-3G | 16 | integrals_LiH-bf16 |
| 4 | STO-3G | 24 | integrals_LiH-bf24 |
| 4 | 6-31G** | 32 | integrals_LiH-bf32 |
| 4 | cc-pVDZ | 32 | integrals_LiH-bf32_dz |
| 4 | cc-pVDZ | 32 | integrals_LiH-bf32_t2 |
| 4 | cc-pCVDZ | 39 | integrals_LiH-bf39 |
| 4 | cc-pVDZ | 48 | integrals_LiH-bf48 |
| 4 | cc-pVDZ | 59 | integrals_LiH-bf59 |

### Li<sub>2</sub>

| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 4 | cc-pVDZ | 40 | integrals_Li2-bf40 |
| 4 | cc-pVDZ | 45 | integrals_Li2-bf45_v6 |
| 4 | cc-pVDZ | 45 | integrals_Li2-bf45_v8 |
| 4 | cc-pVDZ | 48 | integrals_Li2-bf48 |

### OH
| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 4 | cc-pVDZ | 39 | integrals_OH-0-2-bf39 |
| 4 | aug-cc-pVDZ | 59 | integrals_OH-0-2-bf59-noreorient |
| 4 | aug-cc-pVDZ | 59 | integrals_OH-0-2-bf59 |
