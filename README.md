# LiDAR_Camera_Calib
Accurate Lidar-camera Calibration using Feature Edges

**L_C_calib** (Accurate Lidar-camera Calibration using Feature Edges) 
1. A complete calibration system for optimizing poses by using corresponding edges which is suitable for different LiDAR and camera. 

<div align="left">
<img src="Release/data/L_C_calib.gif" width=49.6% />
</div>

**Calib_1-4.exe**
This demonstrates the calibration process:

I.Edge extraction of the target plate in the image—combining manual marking can yield more accurate results;
II.Extraction of the target point cloud of the target plate from the scene point cloud, denoted as PC_t;
III.Edge extraction of the target point cloud from II, denoted as PC_edge_t;
IV.Fitting the ground truth edge of the target plate to the current edge point cloud from III, denoted as gt_t.


**Directly run**
cd Release;
Calib_1-4.exe ./data/1.png ./data/res_all.ply
