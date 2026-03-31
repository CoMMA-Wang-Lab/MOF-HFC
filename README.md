# MOF-HFC
This folder contains the input files required to reproduce the binary mixture grand canonical Monte Carlo (GCMC) simulation of HFC-32 (difluoromethane) and HFC-125 (pentafluoroethane) in Mg-MOF-74 at 300 K and 0.1 bar, as reported in:
> M. Maurya and N. Wang*, "Selective Adsorptive Separation of HFC-32 and HFC-125 in M-MOF-74 (M = Mg, Ni, Co): A Grand Canonical Monte Carlo Study," *The Journal of Physical Chemistry C*, (submitted).

---

## Software 

- **RASPA** version 2.0.37
- Installation instructions: https://github.com/iRASPA/RASPA2

---
## File Descriptions

| File | Description |
|------|-------------|
| `simulation.input` | Main RASPA input file. |
| `MgMOF74.cif` | Crystal structure file for Mg-MOF-74 in CIF format. Used by RASPA to construct the periodic framework. |
| `force_field_mixing_rules.def` | Defines the mixing rules for cross-interaction Lennard–Jones parameters. Lorentz–Berthelot mixing rules are applied throughout. |
| `force_field.def` | Defines custom Lennard–Jones parameters for framework atoms that override the default RASPA force field. |
| `pseudo_atoms.def` | Defines all atom types used in the simulation. |
| `HFC32.def` | Molecule definition file for HFC-32 (CH₂F₂).  |
| `HFC125.def` | Molecule definition file for HFC-125 (CHF₂CF₃).  |

---
## Contact

For questions regarding the simulation setup or force field parameters, please contact: nwang@uttyler.edu.
