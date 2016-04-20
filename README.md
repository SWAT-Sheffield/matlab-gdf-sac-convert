# matlab-gdf-sac-convert

This is a set of matlab functions for reading and writing SAC data in SAC format.
Data is read/written as either binary or ascii.

Mainly useful because this functions have matlab classes which can be used to read write data in hdf5/gdf format using Matlab's hdf5 libraries.

To use these include the hdf5_and_gdf folder in your matlab path.
The main classes of interest are sim_params, sim_data, sim_gridinfo
Which map to the main structures used by the hdf5 standard

For notes see
http://solarwavetheory.blogspot.co.uk/search/label/HDF5
