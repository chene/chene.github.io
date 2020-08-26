---
title: "Procrustes Analysis"
collection: software
type: "Procrustes Analysis placeholder"
permalink: /software/Procrustes_Analysis
date: 2020-08-24
---

Procrustes Analysis refers to the registration between two dataset via a transformation, where elements between datasets have known correspondence. In the context of computer-assisted surgery, Procrustes Analysis menifests as point-to-point, point-to-line, and point-to-surface registration. 

For example, $x_i$ may refer to $i^{th}$ fiducial landmark in a CT volume  and $y_i$ be the corresponding (annotating the same anatomical feature) fiducial in a MRI volume. Given sufficient number of these corresponding landmarks, these two 3D volumes can be aligned/registered.

In general terms, we assume $x_i$ are 3D points, but $y_i$ can be either 3D points, lines, or planes.

### Point-to-Point
* [Orthogonal Procrustes Analysis with isotropic scaling](/software/2020_OPA_isotropic)
* [Orthogonal Procrustes Analysis with anisotropic scaling](/software/2020_AOPA_major)
* [Orthogonal Procrustes Analysis with anisotropic weighting](/software/2020_08-25_AWOPA)

### Point-to-Line

### Point-to-Plane