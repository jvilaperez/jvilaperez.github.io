---
title: 'An adaptive viscosity regularization approach for the numerical solution of
  conservation laws: Application to finite element methods'
authors:
- Ngoc Cuong Nguyen
- Jordi Vila-Pérez
- Jaime Peraire
date: '2023-11-01'
publishDate: '2023-11-07T08:53:28.334891Z'
publication_types:
- article-journal
publication: '*Journal of Computational Physics*'
doi: 10.1016/J.JCP.2023.112507
abstract: We introduce an adaptive viscosity regularization approach for the numerical
  solution of systems of nonlinear conservation laws with shock waves. The approach
  seeks to solve a sequence of regularized problems consisting of the system of conservation
  laws and an additional Helmholtz equation for the artificial viscosity. We propose
  a homotopy continuation of the regularization parameters to minimize the amount
  of artificial viscosity subject to positivity-preserving and smoothness constraints
  on the numerical solution. The regularization methodology is combined with a mesh
  adaptation strategy that identifies the shock location and generates shock-aligned
  meshes, which allows to further reduce the amount of artificial dissipation and
  capture shocks with increased accuracy. We use the hybridizable discontinuous Galerkin
  method to numerically solve the regularized system of conservation laws and the
  continuous Galerkin method to solve the Helmholtz equation for the artificial viscosity.
  We show that the approach can produce approximate solutions that converge to the
  exact solution of the Burgers' equation. Finally, we demonstrate the performance
  of the method on inviscid transonic, supersonic, hypersonic flows in two dimensions.
  The approach is found to be accurate, robust and efficient, and yields very sharp
  yet smooth solutions in a few homotopy iterations.
---
