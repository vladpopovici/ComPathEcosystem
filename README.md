# ComPathEcosystem
Computational Pathology Ecosystem
=================================

This repository is merely an umbrella project used for keeping track of all packages developed
for computational pathology research.
Many libraries and applications are available nowadays for tackling with various research problems
in digital/computational pathology. Here we develop a number of packages and tools to support our
own research. The functionality is spread over a number of libraries to minimized the dependencies
for some use cases and to avoid the conflicts between versions/frameworks needed by some thir party
libraries.

Packages
--------

1. [ComPath](vladpopovici/ComPath) - main computational pathology packages
2. CP_mri - deals with multiresolution images stored as ZARR archives
3. CP_wsi - provides interface to whole slide images (WSI) metadata
4. CP_annot - deals with annotations (normally Polygons or other geometrical primitives)
5. CP_inferno - performs inference - it just applies a model to a WSI
