# Kk1a

[Workpiece index](../README.md#workpieces)

## Geometric pose groups from the 10,000-drop paper runs

Every observed simulated group is included. Moving outcomes are taken at the virtual exit. The stationary runs use a stopped belt from release.

| Belt condition | Observed poses | Geometric groups | Settled drops |
| --- | ---: | ---: | ---: |
| [Moving belt at virtual exit](simulations/20261107_10000/100mm_s/README.md) | 6 | 6 | 8,201 / 10,000 |
| [Stationary belt from release](simulations/20261107_10000/static/README.md) | 15 | 14 | 9,676 / 10,000 |

Each condition is grouped independently. Simulation ranks start at zero and follow descending incidence. The paper label aligns groups through the physical reference orientations where a match is available. Incidence is based on all 10,000 drops.

<details>
<summary>Moving belt at virtual exit: group incidence and member poses</summary>

| Simulation rank | Paper label | Member pose IDs | Settled drops | Incidence |
| ---: | :---: | --- | ---: | ---: |
| 0 | G0 | `Kk1a_0001` | 2,521 | 25.21% |
| 1 | G1 | `Kk1a_0006` | 2,445 | 24.45% |
| 2 | G2 | `Kk1a_0005` | 1,573 | 15.73% |
| 3 | G3 | `Kk1a_0004` | 1,383 | 13.83% |
| 4 | G4 | `Kk1a_0003` | 278 | 2.78% |
| 5 | — | `Kk1a_0002` | 1 | 0.01% |

</details>

<details>
<summary>Stationary belt from release: group incidence and member poses</summary>

| Simulation rank | Paper label | Member pose IDs | Settled drops | Incidence |
| ---: | :---: | --- | ---: | ---: |
| 0 | G0 | `Kk1a_0001` | 2,421 | 24.21% |
| 1 | G1 | `Kk1a_0015` | 2,212 | 22.12% |
| 2 | G2 | `Kk1a_0008` | 1,656 | 16.56% |
| 3 | G3 | `Kk1a_0007` | 1,371 | 13.71% |
| 4 | G4 | `Kk1a_0005` | 1,046 | 10.46% |
| 5 | G5 | `Kk1a_0006` | 943 | 9.43% |
| 6 | — | `Kk1a_0012`, `Kk1a_0014` | 8 | 0.08% |
| 7 | — | `Kk1a_0002` | 4 | 0.04% |
| 8 | — | `Kk1a_0010` | 4 | 0.04% |
| 9 | — | `Kk1a_0003` | 3 | 0.03% |
| 10 | — | `Kk1a_0004` | 3 | 0.03% |
| 11 | — | `Kk1a_0013` | 3 | 0.03% |
| 12 | — | `Kk1a_0009` | 1 | 0.01% |
| 13 | — | `Kk1a_0011` | 1 | 0.01% |

</details>

## 10,000-drop paper study

The stationary series recorded **9,676** settled outcomes. The moving series recorded **8,201** settled outcomes at the virtual exit. Each series contains 10,000 drops.

[Study overview](simulations/20261107_10000/README.md) · [Stationary results](simulations/20261107_10000/static/README.md) · [Moving results](simulations/20261107_10000/100mm_s/README.md)

## Historical pose catalogue

Group numbers rank the saved pose basins by their combined incidence within each observation phase. Pose 0 is the most frequent individual pose in its observation phase. The membership CSV links the displayed numbers to the saved pose IDs. Groups below 1% remain visible.

[Group membership CSV](group_memberships.csv) · [Grouping method](../README.md#catalogue-grouping)

### Transport poses

2,887 settled outcomes across 10,000 historical drops on a 500 mm chute. Incidence uses all completed drops as the denominator.

Outcome counts: settled: 2,887, unsettled: 7,113.

| Pose | Group | Image | Count | Incidence | 95% interval | Share of settled outcomes |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| Pose 0 | Group 0 | ![Kk1a_0001](images/Kk1a_0001.png) | 1585 | 15.85 % | 15.15–16.58 % | 54.90 % |
| Pose 1 | Group 1 | ![Kk1a_0002](images/Kk1a_0002.png) | 1294 | 12.94 % | 12.30–13.61 % | 44.82 % |
| Pose 2 | Group 2 | ![Kk1a_0003](images/Kk1a_0003.png) | 8 | 0.08 % | 0.04–0.16 % | 0.28 % |

[Pose catalogue JSON](poses.json) · [Pose catalogue YAML](poses.yaml) · [Frequencies](frequencies.csv) · [Trial records](trials.csv)

Pose orientations use `xyzw` quaternions from the workpiece frame to the chute frame. Recognition uses the recorded symmetry, a 5° tolerance, and a 1° ambiguity margin. The pose registry reserves previously observed IDs for later recognition.

### Historical run files

- [Configuration](config.json)
- [Manifest](manifest.json)
- [Earlier 1,000-drop comparisons](simulations/README.md)
