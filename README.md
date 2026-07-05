# Edge Contraction Algorithms for the Multicut Problem

This repository contains the implementations of the algorithms used in the bachelor thesis.  
📄 Bachelor Thesis: [Open PDF](./Bachelor-Thesis.pdf)

## Contents

- **`greedy_joining_extended.hxx`**: Implementation of the Greedy-Joining algorithm as well as its extension for parallel edge contraction. This extension determines the contraction set using the *Luby-Jones handshake* algorithm for computing a maximal matching (mode != 'f') or the *Mutex-Kruskal* algorithm for constructing a conflict-free spanning forest (mode = 'f') on undirected, weighted graphs.  
- **`partition.hxx`**: Disjoint-set data structure for node partitioning, used within the algorithms.  

## Usage

The implementations are written in C++ and can be integrated into projects supporting C++17 or higher.
