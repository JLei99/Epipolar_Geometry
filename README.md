# Epipolar_Geometry
1. Generate the Epipolar lines for two different views for the same object.
2. In 3D reconstruction steps we use the world coordinate system consistent with the projection estimated matrices. We obtain solutions for all four distinct cases of the second camera.
- First, we Implement least squares for "triangulating" 3D points corresponding to pairs of matched features that are inliers for estimated E (i.e. consistent with the epipolar geometry).
- Then we compute camera positioning (optical centers and calibrated image centers as 3D points) in the world coordinate system. This is used in data visualization step.
- In visualization step, we visulaizes in 3D both camera positions and triangulated points for four possible cases of the second camera.
We identify one case when solution has 3D points in front of both cameras.
- In the last step, we project 3D points onto each camera, convert to uncalibrated coordinates, and display these projected points together with the original features.
Observe if the are red and blue points are close in each image.
