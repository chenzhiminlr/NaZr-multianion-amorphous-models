# Optimized amorphous models of Na–Zr multi-anion solid electrolytes

Atomic coordinates (VASP POSCAR format; lattice in Å, fractional coordinates) of the optimized amorphous models reported in
*Anion-regulated frameworks enable entropy engineering in sodium halide solid electrolytes* (Nature Communications).

| File | Composition | Atoms |
|---|---|---|
| `NZOC.vasp` | Na20Zr13O10Cl52 | 95 |
| `NZSC.vasp` | Na20Zr13S10Cl52 | 95 |
| `NZOSC.vasp` | Na20Zr13O5S5Cl52 | 95 |
| `NZOSCB.vasp` | Na20Zr13O5S5Cl26Br26 | 95 |

All models use a cubic cell with a = 13.757 Å.

## AIMD initial and final configurations

Initial and final configurations of the 300 K NVT AIMD simulation of each model (VASP POSCAR format; lattice in Å, fractional coordinates, positions only).

| Model | Initial configuration | Final configuration |
|---|---|---|
| NZOC | `NZOC/AIMD_300K_initial.vasp` | `NZOC/AIMD_300K_final.vasp` |
| NZSC | `NZSC/AIMD_300K_initial.vasp` | `NZSC/AIMD_300K_final.vasp` |
| NZOSC | `NZOSC/AIMD_300K_initial.vasp` | `NZOSC/AIMD_300K_final.vasp` |
| NZOSCB | `NZOSCB/AIMD_300K_initial.vasp` | `NZOSCB/AIMD_300K_final.vasp` |

Each final configuration is identical to the corresponding model file listed above.
