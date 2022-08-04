# Optical-Flow

**Dense Optical FLow:** It computes the optical flow vector for every pixel of the frame which may be responsible for its slow speed but leading to a better accurate result. It can be used for detecting motion in the videos, video segmentation, learning structure from motion.

**Lucas-Kanade:** It assumes that the flow is essentially constant in a local neighbourhood of the pixel under consideration, and solves the basic optical flow equations for all the pixels in that neighbourhood, by the least squares criterion.
 
**Horn-Schunck:** It assumes smoothness in the flow over the whole image. Thus, it tries to minimize distortions in flow and prefers solutions which show more smoothness.
