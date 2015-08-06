# Point Cloud Skeletons via Laplacian-Based Contraction
(Automatically exported from code.google.com/p/skeletonization)

## Bibtex

    @inproceedings{cao_smi10,
    author = {Junjie Cao and Andrea Tagliasacchi and Matt Olson and Hao Zhang and Zhixun Su},
    title = {Point Cloud Skeletons via Laplacian-Based Contraction},
    booktitle = {Proc. of IEEE Conf. on Shape Modeling and Applications},
    year = 2015}

## Abstract
We present an algorithm for curve skeleton extraction via Laplacian-based contraction. Our algorithm can be applied to surfaces with boundaries, polygon soups, and point clouds. We develop a contraction operation that is designed to work on generalized discrete geometry data, particularly point clouds, via local Delaunay triangulation and topological thinning. Our approach is robust to noise and can handle moderate amounts of missing data, allowing skeleton-based manipulation of point clouds without explicit surface reconstruction. By avoiding explicit reconstruction, we are able to perform skeleton-driven topology repair of acquired point clouds in the presence of large amounts of missing data. In such cases, automatic surface reconstruction schemes tend to produce incorrect surface topology. We show that the curve skeletons we extract provide an intuitive and easy-to-manipulate structure for effective topology modification, leading to more faithful surface reconstruction. 
