# Data dictionary

## Common abbreviations
- AD: applicability domain.
- GNN: graph neural network.
- pAffinity: model target value derived from kinase bioactivity records.
- RMSE: root mean squared error.
- TPSA: topological polar surface area.
- HBD/HBA: hydrogen-bond donor/acceptor counts.
- MCS: maximum common substructure.

## Ligand codes
- `1`: Maca-1 / Macaflavone I.
- `2`: Maca-2 / Macaflavone II.

## Interpretation notes
- Docking affinity values are in kcal/mol; more negative scores indicate stronger predicted docking affinity within the same docking protocol.
- GNN pAffinity is a computational prediction and is not an experimental affinity measurement.
- `outside-cautious` means the compound is outside the strong applicability domain under the Tanimoto threshold used in the analysis.
- Integrated prioritization is hypothesis-generating and should not be described as experimental validation of kinase inhibition.
