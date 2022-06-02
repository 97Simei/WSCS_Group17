# WSCS_Group17
[![DOI](https://zenodo.org/badge/498253114.svg)](https://zenodo.org/badge/latestdoi/498253114)
## File Description
This is the repositery for the brane programming project in the UvA Web Service and Cloud System course.

- Compute @ ecd4c3b : brane compute package

- braneVisualPackage @ f4db112: brane visualization package

- pipeline.ipynb: brane script of data processing pipeline

## How to Run Pipeline
### Build the packages
```
brane import ZNBai/Compute
brane import 97Simei/braneVisualPackage
```
### Publish the packages
```
brane push computation
brane push visual_test
```
### Under the brane-ide(https://github.com/epi-project/brane-ide) folder
```
make start-ide BRANE_MOUNT_DFS="path to files"
```
Then run the Pipeline.jpynb.
