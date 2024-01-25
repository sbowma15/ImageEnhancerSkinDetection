# ImageEnhancerSkinDetection

The script focuses on image enhancement techniques without explicit skin detection. It includes functions for gamma correction in the LUV color space and RGB thresholding to improve image quality. The script provides a versatile tool for enhancing various aspects of images.

# Functions

1. luv_space_gamma(src, gamma)
Performs gamma correction on the L channel in the LUV color space.
Parameters:
src: Source image in BGR format.
gamma: Gamma value for the power transform.
Returns the gamma-corrected image in RGB format.
2. skin_rgb_threshold(src)
Applies RGB thresholding to enhance specific regions in the image.
Parameters:
src: Source image in BGR format.
Returns the image with enhanced features.
3. find_local_min(hist)
Finds the local minimum in a histogram.
Parameters:
hist: Input histogram.
Returns the threshold and the result of convolution.

This script can be used for general image enhancement, providing flexibility in various image processing applications.
