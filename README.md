# Phylogenetic Trees using ete3 module
Phylogenetic trees, also known as evolutionary trees or cladograms, are graphical representations that depict the evolutionary relationships among different species or groups of organisms. They illustrate the evolutionary history and common ancestry of species based on shared characteristics, genetic information, or other relevant data.

Phylogenetic trees are constructed using various methods and techniques, including molecular sequencing data, anatomical features, fossil records, or a combination of these sources. The tree branches represent the divergence of species over time, with the tips of the branches representing the present-day species or groups and the internal nodes representing common ancestors.

# The Robinson-Foulds (RF) distance
- The Robinson-Foulds (RF) distance is a measure of the difference between two phylogenetic trees. It is based on the concept of bipartitions, which are the ways in which the leaves of a tree can be split into two groups. Each bipartition is represented by a unique set of leaves that fall on one side of a split and another set of leaves that fall on the other side.

- The RF distance between two trees is defined as the number of bipartitions that are present in one tree but not the other. In other words, it is the number of splits that are unique to one tree and not shared by the other.

- The RF distance is a useful measure of tree similarity because it takes into account both the topology of the tree (i.e., the branching pattern) and the leaf labels. It ranges from 0 (identical trees) to the maximum possible number of bipartitions in a tree, which is 2^(n-3) for a tree with n leaves.

- The RF distance is widely used in phylogenetics to compare different trees and to determine which one is more likely to be correct. It is particularly useful for comparing trees that have been inferred using different methods or data sets.

