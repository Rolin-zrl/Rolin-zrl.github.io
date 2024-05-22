---
title: "Point Cloud Registration"
collection: research-experience
type: "Talk"
permalink: /research-experience/2023-01-research-2
venue: "Scientific Research"
start_date: 2023-01-01
end_date: 2024-04-01
location: "Whuhan, China"
---

Point cloud registration is a fundamental problem in computer vision and geometric processing. It aims to find the optimal rigid transformation between sets of points. It has a wide range of applications, including robotics, 3D reconstruction, and object detection.

Point Cloud Registration (PCR) is a fundamental and significant issue in computer vision, aiming to seek the optimal rigid transformation between sets of points. 
Achieving efficient and precise registration of point sets with high outlier rates poses a considerable challenge. We propose an efficient graph-based point cloud registration framework that achieves coarse-to-fine at multi-scales. The overall framework is comprised of two stages. 1) Coarse registration (CR): We develop a graph incorporating micro-structures, employing an efficient graph-based hierarchical strategy to remove outliers for obtaining the maximal consensus set. We propose a robust GNC-Welsch estimator for optimization derived from a robust estimator to the outlier process. The main goal of CR is to achieve fast and robust alignment at a relatively coarse scale. 2) Fine registration (FR): FR's effect is to refine local alignment further at a finer scale. We use the octree approach to search plane features in the micro-structures. By minimizing the distance from the point to the plane, we can obtain a more precise local alignment, and the process will also be addressed effectively by being treated as planar adjustment algorithm combined with Anderson accelerated optimization (PA-AA). After extensive experimental  real data demonstration. Compared to the most advanced methods, our proposed method also performs well on the 3DMatch / ETH datasets, achieving higher accuracy metrics and reducing the time cost by at least one-third. (3DMatch: RE=1.65°, TE=5.75cm; ETH: RE=0.036°, TE=0.81cm).
