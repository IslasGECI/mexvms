# mexvms

R tools to fetch, filter, and analyze Mexican Vessel Monitoring System (VMS) data. Provides tidyverse-friendly access to vessel tracks, metadata, and spatial summaries, enabling reproducible workflows for fisheries science and conservation.

These functions retrieve data from the Mexican fisheries data set:

- `fetch_segments()`: Retrieve summary metadata about VMS segments
- `fetch_spatial_features()`: Retrieve static spatial or environmental features
- `fetch_vessels()`: Retrieve a list of distinct vessels
- `fetch_vessel_info()`: Retrieve vessel registry metadata
- `fetch_vms_raster()`: Retrieve a raster or binned table of coordinates, allowing the user to specify variables to report (e.g., hours, active hours)
- `fetch_vms_tracks()`: Retrieve VMS tracking data
