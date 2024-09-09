Linux_ Python Version -> 3.8 [Working]
conda activate ObjectDatasetTools2
pip install numpy Cython==0.28.2 pypng scipy scikit-learn open3d==0.16.0 scikit-image tqdm pykdtree opencv-python==4.6.0.66 opencv-contrib-python==4.6.0.66 trimesh==2.38.24

Attempting uninstall: scipy
    Found existing installation: scipy 1.10.1
    Uninstalling scipy-1.10.1:
      Successfully uninstalled scipy-1.10.1
Attempting uninstall: numpy
    Found existing installation: numpy 1.24.4
    Uninstalling numpy-1.24.4:
      Successfully uninstalled numpy-1.24.4

(ObjectDatasetTools2) nishanth@Bright-PC:/usr/workout/ObjectDatasetTools$ python compute_gt_poses.py LINEMOD/box 
(ObjectDatasetTools2) nishanth@Bright-PC:/usr/workout/ObjectDatasetTools$ python register_scene.py LINEMOD/box
pip install shapely
/home/nishanth/anaconda3/envs/ObjectDatasetTools2/lib/python3.8/site-packages/trimesh/grouping.py -> changes adding np.bool = np.bool_
/home/nishanth/anaconda3/envs/ObjectDatasetTools2/lib/python3.8/site-packages/trimesh/grouping.py -> changed np.float to float
