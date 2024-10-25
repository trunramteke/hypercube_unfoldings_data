# Complete Dimension-Descending Tilers: Proof for the 4D Hypercube

## Result
This repository contains the computational verification and data supporting the proof of a long-standing conjecture in geometric topology: that every face-unfolding of the 4-dimensional hypercube has an edge-unfolding that tiles the plane. This result completes the classification of the hypercube as a "complete dimension-descending tiler" (c-DDT), resolving a question that had remained open since the initial exploration of hypercube unfoldings by Turney in 1984-85.

## Historical Context
The journey toward this result spans several decades:
- 1984-85: P. Turney established the 261 distinct face-unfoldings of the 4D hypercube
- 2015: Diaz and O'Rourke proved the first case of a hypercube face-unfolding with a plane-tiling edge-unfolding
- 2016: Langerman and Winslow demonstrated the Dali Cross case
- 2022: This work completes the journey by proving that ALL face-unfoldings have plane-tiling edge-unfoldings

## Publication
The proof was presented at the Japan Conference on Discrete and Computational Geometry, Graphs, and Games (JCDCG³ 2022):
- Conference Proceedings: [JCDCG³ 2022 Proceedings, p. 100](https://www.rs.tus.ac.jp/jcdcggg/JCDCG3-2022Proceedings(r2).pdf)

## Key Contributions
- First complete proof that every face-unfolding of the hypercube has an edge-unfolding that tiles ℝ²
- Development of an algorithmic approach using Hamiltonian paths for enumeration
- Verification of linear unfoldings for all 261 cases
- Computational data supporting the theoretical proof

## Repository Structure
```
└── results/
    └── [Complete coordinate data for all edge-unfoldings in JSON format]
```

## Methodology
The proof builds upon:
- Turney's classification of the 261 face-unfoldings
- Firet's theorem on linear unfoldings
- Novel algorithmic approach using Hamiltonian paths for enumeration
- Computational verification across all cases

## Data Format
- Comprehensive JSON-formatted coordinates for all edge-unfoldings
- Each unfolding follows the numbering system established by [FU Berlin Mathematics](https://page.mi.fu-berlin.de/moritz/mo/198722/unfoldings)
- Special cases like the Dali Cross (Unfolding_213) are specifically annotated

## Citation
If you use this work in your research, please cite:
```
Ramteke, T. V. (2022). Unfoldings of 4D-Hypercube Unfoldings that tile ℝ². 
In Proceedings of JCDCG³ 2022 (p. 100)
```
