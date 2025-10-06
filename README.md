# 📖 Study of Cospectral Graphs

This repository contains a detailed study into the field of **spectral graph theory**, with a specific focus on **cospectral graphs**. It explores the relationship between the algebraic properties of matrices associated with a graph and the combinatorial structure of the graph itself.

---

## Table of Contents
- [About This Project](#about-this-project)
- [1. Foundations of Spectral Graph Theory and Cospectrality](#1-foundations-of-spectral-graph-theory-and-cospectrality)
  - [1.1 The Spectrum of a Graph: An Algebraic Fingerprint](#11-the-spectrum-of-a-graph-an-algebraic-fingerprint)
  - [1.2 A Menagerie of Matrices: Defining the Spectra](#12-a-menagerie-of-matrices-defining-the-spectra)

---

## About This Project

The study of cospectral graphs lies at the heart of spectral graph theory, a discipline that bridges the combinatorial world of graph structures with the algebraic realm of linear algebra. This field investigates the profound and often subtle relationships between the properties of a graph and the eigenvalues of matrices associated with it.

The central question that motivates this study is one of limits: **What can the spectrum of a graph tell us about its structure, and, more importantly, what can it not?** This inquiry originated from a tantalizingly simple—yet ultimately false—conjecture that a graph's spectrum could serve as a unique identifier, a complete algebraic fingerprint. The failure of this conjecture gave rise to a rich and complex field dedicated to understanding those "algebraic accidents"—non-isomorphic graphs that share the same spectrum.

This project establishes the necessary theoretical background, defines the key objects of study, and explores the historical context that gave birth to this fascinating area of mathematics.

---

## 1. Foundations of Spectral Graph Theory and Cospectrality

### 1.1 The Spectrum of a Graph: An Algebraic Fingerprint

Spectral graph theory is the study of a graph's properties in relation to the characteristic polynomial, eigenvalues, and eigenvectors of matrices associated with the graph. The fundamental idea is to translate a combinatorial object—a graph—into an algebraic one—a matrix—and then use the powerful tools of linear algebra to deduce structural information about the original graph. The multiset of eigenvalues of such a matrix is referred to as the **spectrum of the graph**.

A crucial property of the spectrum is that it is a **graph invariant**. This means that if two graphs, $G$ and $H$, are isomorphic ($G \cong H$), then they are necessarily cospectral. Isomorphic graphs are structurally identical, differing only in the labeling of their vertices. An isomorphism from $G$ to $H$ can be represented by a permutation matrix $P$ such that $A_H = P^T A_G P$, where $A_G$ and $A_H$ are the adjacency matrices. Since this is a similarity transformation, it preserves all eigenvalues.

However, the converse is not true. The spectrum is **not a complete invariant**. There exist pairs of graphs that are non-isomorphic but share the same spectrum. Such graphs are called **cospectral** or **isospectral**. The existence of these "cospectral mates" demonstrates the inherent limitations of using spectral properties alone to distinguish between graphs.

### 1.2 A Menagerie of Matrices: Defining the Spectra

While the adjacency matrix is the most common starting point, spectral graph theory employs a variety of matrices, each offering a different algebraic lens through which to view a graph's structure.

-   **The Adjacency Matrix ($A$)**
    .

-   **The Laplacian Matrix ($L$)**
   

-   **The Signless Laplacian Matrix ($Q$)**
   

-   **The Normalized Laplacian ($\mathcal{L}$)**

-  **Other Matrices**
