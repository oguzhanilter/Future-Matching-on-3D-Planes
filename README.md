# Future Matching on 3D Planes 
An algorithm exploiting deep monocular depth to improve image feature matching.

# Abstract
In this project, we propose an algorithm exploiting deep monocular depth to improve image feature matching.
Using the monocular depth, we find multiple quasi-3D planes in each image that are then matched using deep learned similarity scores and the HDBSCAN clustering algorithm. 
We form tentative point correspondences on the RGB images by constraining the problem to matching the features on plane-to-plane correspondences, reducing combinatorics of the matching problem significantly. 
The approach can be used with any feature detector, e.g., SIFT and SuperPoint. 
We show on publicly available real-world datasets that the increased inlier ratio by the proposed approach allows finding more accurate relative poses than by using the traditional approaches. 

# Availability 
The source code will be made publicly available as soon as we publish the paper in [arxiv](https://arxiv.org/).
