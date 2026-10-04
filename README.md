Here we develop an end-to-end AI solution for cloud and cloud shadow masking from multi-spectral satellite imagery. The data to be used is a subset from the CloudSen12+ dataset. 

From this dataset, which contains four classes: Clear (0), Thick Cloud (1), Thin Cloud (2), and Cloud Shadow (3), we want to develop a semantic segmentation model that classifies every pixel into

| Label | Class Name | Description |
|---|---|---|
| 0 | Clear | Clear |
| 1 | Cloud | Cloud |
| 2 | Cloud Shadow | Cloud Shadow  |

Thus a remapping must be done. Clear --> (0), Thick and Thin Cloud --> (1), and Cloud Shadow --> (2).  
