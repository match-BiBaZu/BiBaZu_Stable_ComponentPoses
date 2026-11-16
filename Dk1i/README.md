# Dk1i

[Workpiece index](../README.md#workpieces)

## Geometric pose groups from the 10,000-drop paper runs

Every observed simulated group is included. Moving outcomes are taken at the virtual exit. The stationary runs use a stopped belt from release.

| Belt condition | Observed poses | Geometric groups | Settled drops |
| --- | ---: | ---: | ---: |
| [Moving belt at virtual exit](simulations/20261107_10000/100mm_s/README.md) | 8 | 6 | 9,950 / 10,000 |
| [Stationary belt from release](simulations/20261107_10000/static/README.md) | 32 | 21 | 10,000 / 10,000 |

Each condition is grouped independently. Simulation ranks start at zero and follow descending incidence. The paper label aligns groups through the physical reference orientations where a match is available. Incidence is based on all 10,000 drops.

<details>
<summary>Moving belt at virtual exit: group incidence and member poses</summary>

| Simulation rank | Paper label | Member pose IDs | Settled drops | Incidence |
| ---: | :---: | --- | ---: | ---: |
| 0 | G0 | `Dk1i_0003`, `Dk1i_0005` | 3,334 | 33.34% |
| 1 | G1 | `Dk1i_0002`, `Dk1i_0004` | 3,237 | 32.37% |
| 2 | G2 | `Dk1i_0007` | 1,174 | 11.74% |
| 3 | G3 | `Dk1i_0006` | 1,089 | 10.89% |
| 4 | G4 | `Dk1i_0001` | 602 | 6.02% |
| 5 | G5 | `Dk1i_0008` | 514 | 5.14% |

</details>

<details>
<summary>Stationary belt from release: group incidence and member poses</summary>

| Simulation rank | Paper label | Member pose IDs | Settled drops | Incidence |
| ---: | :---: | --- | ---: | ---: |
| 0 | G0 | `Dk1i_0013`, `Dk1i_0014` | 3,333 | 33.33% |
| 1 | G1 | `Dk1i_0012`, `Dk1i_0015` | 3,250 | 32.50% |
| 2 | G2 | `Dk1i_0030` | 1,103 | 11.03% |
| 3 | G3 | `Dk1i_0003`, `Dk1i_0005`, `Dk1i_0008`, `Dk1i_0016` | 1,070 | 10.70% |
| 4 | G4 | `Dk1i_0001`, `Dk1i_0002` | 625 | 6.25% |
| 5 | G5 | `Dk1i_0031`, `Dk1i_0032` | 563 | 5.63% |
| 6 | — | `Dk1i_0027` | 10 | 0.10% |
| 7 | — | `Dk1i_0004`, `Dk1i_0006`, `Dk1i_0009`, `Dk1i_0011` | 9 | 0.09% |
| 8 | — | `Dk1i_0023` | 6 | 0.06% |
| 9 | — | `Dk1i_0007`, `Dk1i_0010` | 5 | 0.05% |
| 10 | — | `Dk1i_0019` | 4 | 0.04% |
| 11 | — | `Dk1i_0024` | 4 | 0.04% |
| 12 | — | `Dk1i_0026` | 4 | 0.04% |
| 13 | — | `Dk1i_0022` | 3 | 0.03% |
| 14 | — | `Dk1i_0025` | 3 | 0.03% |
| 15 | — | `Dk1i_0020` | 2 | 0.02% |
| 16 | — | `Dk1i_0029` | 2 | 0.02% |
| 17 | — | `Dk1i_0017` | 1 | 0.01% |
| 18 | — | `Dk1i_0018` | 1 | 0.01% |
| 19 | — | `Dk1i_0021` | 1 | 0.01% |
| 20 | — | `Dk1i_0028` | 1 | 0.01% |

</details>

## Catalogue rebuilt from 10,000 drops

Rebuilt on 16 November 2026 from the completed [20261107_10000 moving-belt study](simulations/20261107_10000/100mm_s/README.md). No new simulation trials were run. The archived reference settings are used (belt/wall friction 0.10/0.05 and first-second weight impulses); the older 1,000-trial catalogue used an earlier protocol.

Pose classes retain the recorded symmetry, 5° tolerance and 1° ambiguity margin. Historical IDs are reused only for unique unambiguous anchor matches; all historical registry anchors remain reserved. Groups use the unchanged published simulator rules, ordered by combined incidence. Rare groups remain visible. Review rows remain separate. No disturbance stability representatives were inferred.

[JSON](poses.json) · [YAML](poses.yaml) · [Memberships](group_memberships.csv) · [Trials](trials.csv) · [Configuration](config.json) · [Validation](validation.json)

## Moving-belt transport poses

9,950 settled observations from 10,000 drops. Incidence uses all drops.

| Pose | Saved ID | Group | Image | Count | Incidence | 95% interval |
| --- | --- | --- | --- | ---: | ---: | ---: |
| 0 | Dk1i_0003 | Group 0 | ![Dk1i_0003](images/catalogue_20261116_10000/Dk1i_0003.png) | 1700 | 17.00% | 16.28–17.75% |
| 1 | Dk1i_0005 | Group 0 | ![Dk1i_0005](images/catalogue_20261116_10000/Dk1i_0005.png) | 1634 | 16.34% | 15.63–17.08% |
| 2 | Dk1i_0002 | Group 1 | ![Dk1i_0002](images/catalogue_20261116_10000/Dk1i_0002.png) | 1630 | 16.30% | 15.59–17.04% |
| 3 | Dk1i_0004 | Group 1 | ![Dk1i_0004](images/catalogue_20261116_10000/Dk1i_0004.png) | 1607 | 16.07% | 15.36–16.80% |
| 4 | Dk1i_0007 | Group 2 | ![Dk1i_0007](images/catalogue_20261116_10000/Dk1i_0007.png) | 1174 | 11.74% | 11.12–12.39% |
| 5 | Dk1i_0006 | Group 3 | ![Dk1i_0006](images/catalogue_20261116_10000/Dk1i_0006.png) | 1089 | 10.89% | 10.29–11.52% |
| 6 | Dk1i_0001 | Group 4 | ![Dk1i_0001](images/catalogue_20261116_10000/Dk1i_0001.png) | 602 | 6.02% | 5.57–6.50% |
| 7 | Dk1i_0008 | Group 5 | ![Dk1i_0008](images/catalogue_20261116_10000/Dk1i_0008.png) | 514 | 5.14% | 4.72–5.59% |

[Post-braking JSON](poses_after_stop.json) · [Post-braking YAML](poses_after_stop.yaml) · [Post-braking trials](trials_after_stop.csv)

## Resting poses after belt stop

10,000 settled observations from 10,000 drops. Incidence uses all drops.

| Pose | Saved ID | Group | Image | Count | Incidence | 95% interval |
| --- | --- | --- | --- | ---: | ---: | ---: |
| 0 | Dk1i_stop_0002 | Group 0 | ![Dk1i_stop_0002](images/catalogue_20261116_10000/Dk1i_stop_0002.png) | 1700 | 17.00% | 16.28–17.75% |
| 1 | Dk1i_stop_0005 | Group 0 | ![Dk1i_stop_0005](images/catalogue_20261116_10000/Dk1i_stop_0005.png) | 1634 | 16.34% | 15.63–17.08% |
| 2 | Dk1i_stop_0003 | Group 1 | ![Dk1i_stop_0003](images/catalogue_20261116_10000/Dk1i_stop_0003.png) | 1630 | 16.30% | 15.59–17.04% |
| 3 | Dk1i_stop_0004 | Group 1 | ![Dk1i_stop_0004](images/catalogue_20261116_10000/Dk1i_stop_0004.png) | 1607 | 16.07% | 15.36–16.80% |
| 4 | Dk1i_stop_0007 | Group 2 | ![Dk1i_stop_0007](images/catalogue_20261116_10000/Dk1i_stop_0007.png) | 1176 | 11.76% | 11.14–12.41% |
| 5 | Dk1i_stop_0006 | Group 3 | ![Dk1i_stop_0006](images/catalogue_20261116_10000/Dk1i_stop_0006.png) | 1094 | 10.94% | 10.34–11.57% |
| 6 | Dk1i_stop_0001 | Group 4 | ![Dk1i_stop_0001](images/catalogue_20261116_10000/Dk1i_stop_0001.png) | 602 | 6.02% | 5.57–6.50% |
| 7 | Dk1i_stop_0008 | Group 5 | ![Dk1i_stop_0008](images/catalogue_20261116_10000/Dk1i_stop_0008.png) | 557 | 5.57% | 5.14–6.04% |

## Preserved history and source data

The original 10,000-drop simulation archives and all earlier grouping/validation studies are unchanged. The prior 1,000-trial catalogue's top-level files and images are preserved in the history snapshot.

[Previous catalogue snapshot](history/catalogue_before_10000_20261116.tar.xz) · [Snapshot checksums](history/catalogue_before_10000_20261116.contents.json) · [Derivation provenance](catalogue/20261116_10000/provenance.json) · [Transport grouping evidence](catalogue/20261116_10000/transport_grouping.json.gz) · [Post-braking grouping evidence](catalogue/20261116_10000/after_stop_grouping.json.gz)

[Stationary and moving source runs](simulations/20261107_10000/README.md). The existing simulation_results.zip, when present, is the preserved historical 1,000-trial run.

Checksums refer to committed Git bytes; Windows checkout line endings may differ.
