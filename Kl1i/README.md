# Kl1i

[Workpiece index](../README.md#workpieces)

## Geometric pose groups from the 10,000-drop paper runs

Every observed simulated group is included. Moving outcomes are taken at the virtual exit. The stationary runs use a stopped belt from release.

| Belt condition | Observed poses | Geometric groups | Settled drops |
| --- | ---: | ---: | ---: |
| [Moving belt at virtual exit](simulations/20261107_10000/100mm_s/README.md) | 6 | 6 | 9,999 / 10,000 |
| [Stationary belt from release](simulations/20261107_10000/static/README.md) | 7 | 6 | 9,997 / 10,000 |

Each condition is grouped independently. Simulation ranks start at zero and follow descending incidence. The paper label aligns groups through the physical reference orientations where a match is available. Incidence is based on all 10,000 drops.

<details>
<summary>Moving belt at virtual exit: group incidence and member poses</summary>

| Simulation rank | Paper label | Member pose IDs | Settled drops | Incidence |
| ---: | :---: | --- | ---: | ---: |
| 0 | G0 | `Kl1i_0001` | 4,696 | 46.96% |
| 1 | G1 | `Kl1i_0006` | 4,551 | 45.51% |
| 2 | G2 | `Kl1i_0003` | 381 | 3.81% |
| 3 | G3 | `Kl1i_0002` | 326 | 3.26% |
| 4 | — | `Kl1i_0004` | 25 | 0.25% |
| 5 | — | `Kl1i_0005` | 20 | 0.20% |

</details>

<details>
<summary>Stationary belt from release: group incidence and member poses</summary>

| Simulation rank | Paper label | Member pose IDs | Settled drops | Incidence |
| ---: | :---: | --- | ---: | ---: |
| 0 | G0 | `Kl1i_0001` | 4,596 | 45.96% |
| 1 | G1 | `Kl1i_0007` | 4,596 | 45.96% |
| 2 | G2 | `Kl1i_0004` | 419 | 4.19% |
| 3 | G3 | `Kl1i_0003`, `Kl1i_0006` | 321 | 3.21% |
| 4 | — | `Kl1i_0002` | 40 | 0.40% |
| 5 | — | `Kl1i_0005` | 25 | 0.25% |

</details>

## 10,000-drop paper study

The stationary series recorded **9,997** settled outcomes. The moving series recorded **9,999** settled outcomes at the virtual exit. Each series contains 10,000 drops.

[Study overview](simulations/20261107_10000/README.md) · [Stationary results](simulations/20261107_10000/static/README.md) · [Moving results](simulations/20261107_10000/100mm_s/README.md)

## Historical pose catalogue

Group numbers rank the saved pose basins by their combined incidence within each observation phase. Pose 0 is the most frequent individual pose in its observation phase. The membership CSV links the displayed numbers to the saved pose IDs. Groups below 1% remain visible.

[Group membership CSV](group_memberships.csv) · [Grouping method](../README.md#catalogue-grouping)

### Transport poses

9,333 settled outcomes across 10,000 historical drops on a 500 mm chute. Incidence uses all completed drops as the denominator.

Outcome counts: settled: 9,333, unsettled: 667.

| Pose | Group | Image | Count | Incidence | 95% interval | Share of settled outcomes |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| Pose 0 | Group 0 | ![Kl1i_0001](images/Kl1i_0001.png) | 4757 | 47.57 % | 46.59–48.55 % | 50.97 % |
| Pose 1 | Group 1 | ![Kl1i_0002](images/Kl1i_0002.png) | 4576 | 45.76 % | 44.79–46.74 % | 49.03 % |

[Pose catalogue JSON](poses.json) · [Pose catalogue YAML](poses.yaml) · [Frequencies](frequencies.csv) · [Trial records](trials.csv)

Pose orientations use `xyzw` quaternions from the workpiece frame to the chute frame. Recognition uses the recorded symmetry, a 5° tolerance, and a 1° ambiguity margin. The pose registry reserves previously observed IDs for later recognition.

### Historical run files

- [Configuration](config.json)
- [Manifest](manifest.json)
- [Earlier 1,000-drop comparisons](simulations/README.md)
