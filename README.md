# Car detection and localization
Car detection and localization is used to detect bounding box where a vehicle exists, by using this data along with depth map -obtained by e.g,. LIDAR or stereo-vision- we can compute the nearest point hence determine distance toof collision.

The following approach is used:
1.	Extract HOG and YUV color space features from training data.
2.	Train SVM using cross-validation for parameters tuning.
3.	Use sliding window algorithm with different sizes.
