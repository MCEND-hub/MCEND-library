# MCEND basis set library

This is the library that contains the [MCEND]() basis sets. The basis sets were generated using [Psi4] and Python scripts as included in the [MCEND-tools]() repository.

Since MCEND is an electron-nuclead dynamics package, the basis sets that are used contain electronic and nuclear degrees of freedom. They are therefore no electronic, but electron-nuclear basis sets, specific to the kind of molecule. 

The nuclear basis is further set up on an interpolated grid using the information in the basis set library.

For any changes to the settings of nuclear or electronic basis, you need to generate a new basis set (or select one from the library).

## Contents
At the moment, the basis set library contains the following basis sets. The number of remaining electronic basis functions is a result of the numerical threshold that was set to exclude numerically dependent orbitals. The overlap of the orbitals is found in the file `smateigvals.n`, from where the threshold can be deduced. The nuclear grid points and information about the basis set can be found in the `rsp_MOLECULE` and `info-MOLECULE.dat` files.

### H~2~

| Number of nuclear grid points | Originating electronic basis | Remaining electronic basis functions | Name of the basis set |
| -- | -- | -- | -- |
| 4 | cc-pVDZ | 17 | integrals_H2-1-2-bf17 |
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

### He~2~

### BeH<sup>+</sup> 

### Be~2~

### LiH

### Li~2~

### O~2~

### OH
