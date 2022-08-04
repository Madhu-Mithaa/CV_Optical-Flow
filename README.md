# Optical-Flow
# Feature Detection/Descriptor/Matching

**ORB** : ORB is basically a fusion of FAST key point detector and BRIEF descriptor with many modifications to enhance the performance.

          Advantage  - ORB is rotation invariant and resistant to noise
          
          Limitation - Mathematically complicated and computationally heavy 
          
**SURF** : Simply an upgraded version of SIFT.

          Advantage  - Fast and robust algorithm for local, similarity invariant representation and comparison of images.
          
          Limitation - High dimension of feature descriptor, large amount of computation, and low matching accuracy when the angle of rotation and angle of view is too large.
          
**SIFT** : Used to detect corners, blobs, circles, and so on. It is also used for scaling an image.

          Advantage  - It can generate large numbers of features that densely cover the image over the full range scales and locations.
          
          Limitation - Quite slow, costs long time, and is not effective for low powered devices
          
**Haris Corner** : Used to detect corners in an input image

                   Advantage  - Takes the differential of the corner score into account with reference to direction directly, instead of using shifting patches for every 45-degree angle, and has been proved to be more accurate in distinguishing between edges and corners.
                   
                   Limitation - Need to set a different threshold for each image in order to detect the most important interesting points
                   
 
