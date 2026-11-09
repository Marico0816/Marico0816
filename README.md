# Selected research and projects

## Temporal Evidence Fusion (TEF)

TEF reconstructs a surface mesh from LiDAR scans with known sensor poses. It groups scans into short temporal blocks and combines evidence from surface hits and rays that pass through free space. The fused field is then used to extract a triangle mesh.

The Python implementation includes a CPU demo that reconstructs a floor and a cylindrical wall from 12 synthetic scans, dataset converters for Newer College and Oxford Spires, and scripts for evaluating reconstructed surfaces. The validation notes describe how the released code compares with the research implementation.

[Code and setup](https://github.com/Marico0816/TEF) · [Run the CPU demo](https://github.com/Marico0816/TEF#sanity-test-no-dataset-needed) · [Validation notes](https://github.com/Marico0816/TEF/blob/main/docs/validation.md)

## Digital Spherimeter

A team project for calculating areas on a sphere. It estimates country areas from geographic boundaries and lets users draw regions for interactive area calculation.

[Project repository](https://github.com/Marico0816/digital-spherimeter)
