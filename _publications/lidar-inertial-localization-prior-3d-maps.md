```markdown
---
title: "LiDAR-Inertial Localization with Prior 3D Maps in GNSS-Challenged Environments"
collection: publications
category: manuscripts
permalink: /publication/lidar-inertial-localization-prior-3d-maps
excerpt: "A real-time localization framework combining LiDAR–inertial odometry, NDT-based scan-to-map matching, local map retrieval, and sliding-window factor-graph optimization for accurate localization in large-scale GNSS-challenged environments."
date: 2026-07-11
venue: "Manuscript"
paperurl: "/files/lidar-inertial-localization-prior-3d-maps.pdf"
citation: 'Abraha, E., Aldibaja, M., and Istenes, Z. (2026). &quot;LiDAR-Inertial Localization with Prior 3D Maps in GNSS-Challenged Environments.&quot; <i>Manuscript</i>.'
---

## Authors

**Eliyas Abraha**  
Smart Mechatronics and Robotics Research Group  
Saxion University of Applied Sciences  
Enschede, The Netherlands  
[e.k.abraha@saxion.nl](mailto:e.k.abraha@saxion.nl)

**Mohammad Aldibaja**  
Smart Mechatronics and Robotics Research Group  
Saxion University of Applied Sciences  
Enschede, The Netherlands  
[m.a.j.aldibaja@saxion.nl](mailto:m.a.j.aldibaja@saxion.nl)

**Zoltan Istenes**  
Faculty of Informatics  
ELTE Eötvös Loránd University  
Budapest, Hungary  
[zoltan.istenes@elte.hu](mailto:zoltan.istenes@elte.hu)

## Abstract

Reliable localization in large-scale, GNSS-challenged environments remains a fundamental problem for autonomous robots. This paper presents a real-time localization framework that estimates a robot’s pose with respect to a predefined 3D point-cloud map. The proposed system combines LiDAR–inertial odometry with global map-based localization constraints to provide accurate and drift-resilient pose estimation.

Global pose estimation is achieved by geometrically aligning the current LiDAR scan with a local submap using NDT-OMP, an OpenMP-parallelized implementation of the Normal Distributions Transform. This approach enables computationally efficient scan matching and robust convergence in large-scale environments. To improve scalability, a local map-retrieval strategy restricts scan-to-map registration to spatially relevant regions of the global map.

A sliding-window factor graph integrates high-rate LiDAR–inertial odometry estimates with global map-based constraints, enabling continuous pose estimation and correction of accumulated drift. Experiments conducted using benchmark and custom datasets demonstrate centimetre- to decimetre-level localization accuracy while maintaining real-time performance. The results validate the effectiveness of the proposed framework for autonomous robotic operation in large-scale, GNSS-denied and GNSS-degraded environments.
```
