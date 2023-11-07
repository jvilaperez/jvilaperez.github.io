---
title: Optimal transport for mesh adaptivity and shock capturing of compressible flows
authors:
- Ngoc Cuong Nguyen
- R. Loek Van Heyningen
- Jordi Vila-Perez
- Jaime Peraire
date: '2023-10-01'
publishDate: '2023-11-07T08:53:28.325250Z'
publication_types:
- manuscript
publication: '*(Submitted)*'
abstract: We present an optimal transport approach for mesh adaptivity and shock capturing
  of compressible flows. Shock capturing is based on a viscosity regularization of
  the governing equations by introducing an artificial viscosity field as solution
  of the Helmholtz equation. Mesh adaptation is based on the optimal transport theory
  by formulating a mesh mapping as solution of Monge-Ampere equation. The marriage
  of optimal transport and viscosity regularization for compressible flows leads to
  a coupled system of the compressible Euler/Navier-Stokes equations, the Helmholtz
  equation, and the Monge-Ampere equation. We propose an iterative procedure to solve
  the coupled system in a sequential fashion using homotopy continuation to minimize
  the amount of artificial viscosity while enforcing positivity-preserving and smoothness
  constraints on the numerical solution. We explore various mesh monitor functions
  for computing r-adaptive meshes in order to reduce the amount of artificial dissipation
  and improve the accuracy of the numerical solution. The hybridizable discontinuous
  Galerkin method is used for the spatial discretization of the governing equations
  to obtain high-order accurate solutions. Extensive numerical results are presented
  to demonstrate the optimal transport approach on transonic, supersonic, hypersonic
  flows in two dimensions. The approach is found to yield accurate, sharp yet smooth
  solutions within a few mesh adaptation iterations.
tags:
- artificial viscosity
- compressible flows
- discontinuous Galerkin methods
- finite element methods
- mesh adaptation
- optimal transport
- shock capturing
links:
- name: URL
  url: https://arxiv.org/abs/2310.01196v1
---
