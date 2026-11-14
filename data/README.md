# Data

The three files are the HVR_1 network from the `malaria_genes` collection on
[Netzschleuder](https://networks.skewed.de/net/malaria_genes), which comes from
Larremore, Clauset and Buckee (2013).

| File | Content |
|------|---------|
| `edges.csv` | 2812 undirected edges, as source and target node indices |
| `nodes.csv` | 307 nodes: index, name, CysPoLV class (1 to 6), UPS class (-1, 1, 2, 3) and the layout position used for the plots |
| `gprops.csv` | Network metadata: name, description, citation and URL |

Each node is a var gene sequence (DBLa domain of the PfEMP1 protein), and an
edge links two sequences that share a significant exact match.

The CysPoLV class (cysteine count and positions of limited variability) and
the UPS class (upstream promoter region, A, B or C; -1 when none was
identified) are existing biological classifications, used as reference
partitions to interpret the communities.

## Source

Larremore, D. B., Clauset, A. and Buckee, C. O. (2013). A Network Approach to
Analyzing Highly Recombinant Malaria Parasite Genes. PLOS Computational
Biology, 9(10), e1003268. https://doi.org/10.1371/journal.pcbi.1003268