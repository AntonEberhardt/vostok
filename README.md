# vostok
VOSTOK, The Voxel Octree Solar Toolkit, is a command-line tool to compute a detailed model of incoming solar radiation distribution on a patch of land, including structures like buildings and vegetation, represented by a 3D point cloud data set. 

VOSTOK is written in C++ and makes use of the "solpos.h" library to compute the angular position of the sun in the sky for a given moment in time, created by the U.S. Department of Energy National Renewable Energy Laboratory ( http://rredc.nrel.gov/solar/codesandalgorithms/solpos/ ) and released under the public domain.