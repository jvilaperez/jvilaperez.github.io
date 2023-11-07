---
title: A non-oscillatory face-centred finite volume method for compressible flows
authors:
- J. Vila-Pérez
- M. Giacomini
- R. Sevilla
- A. Huerta
date: '2022-01-01'
publishDate: '2023-11-07T08:53:28.268960Z'
publication_types:
- article-journal
publication: '*Computers and Fluids*'
doi: 10.1016/j.compfluid.2021.105272
abstract: This work presents a face-centred finite volume (FCFV) paradigm for the
  simulation of compressible flows. The FCFV method defines the unknowns at the face
  barycentre and uses a hybridisation procedure to eliminate all the degrees of freedom
  inside the cells. In addition, Riemann solvers are defined implicitly within the
  expressions of the numerical fluxes. The resulting methodology provides first-order
  accurate approximations of the conservative quantities, i.e. density, momentum and
  energy, as well as of the viscous stress tensor and of the heat flux, without the
  need of any gradient reconstruction procedure. Hence, the FCFV solver preserves
  the accuracy of the approximation in presence of distorted and highly stretched
  cells, providing a solver insensitive to mesh quality. In addition, FCFV is capable
  of constructing non-oscillatory approximations of sharp discontinuities without
  resorting to shock capturing or limiting techniques. For flows at low Mach number,
  the method is robust and is capable of computing accurate solutions in the incompressible
  limit without the need of introducing specific pressure correction strategies. A
  set of 2D and 3D benchmarks of external flows is presented to validate the methodology
  in different flow regimes, from inviscid to viscous laminar flows, from transonic
  to subsonic incompressible flows, demonstrating its potential to handle compressible
  flows in realistic scenarios.
tags:
- Compressible flows
- Face-centred
- Finite volume method
- Hybridisable discontinuous Galerkin
- Incompressible limit
- Riemann solvers
---
