# VoxelMap

## Introduction
**VoxelMap** is an efficient and probabilistic adaptive(coarse-to-fine) voxel mapping method for 3D LiDAR. Unlike the point cloud map, VoxelMap uses planes as representation units. A scan of LiDAR data will generate or update the plane. Each plane contains its own plane parameters and uncertainties that need to be estimated. This repo shows how to integrate VoxelMap into a LiDAR odometry.


This repository adds support for the Ouster LiDAR. 
