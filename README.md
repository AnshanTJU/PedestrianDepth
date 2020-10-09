# Real-time Monocular Pedestrian Depth Estimation and Segmentation on Embedded Systems

This is the Pytorch implementation of our article: Shan An, Fangru Zhou, Mei Yang, Haogang Zhu, Changhong Fu, and Konstantinos A. Tsintotas. Real-time Monocular Pedestrian Depth Estimation and Segmentation on Embedded Systems. Submitted to ICRA 2021.

**Abstract:** 

Depth estimation to achieve collision avoidance against moving pedestrians is a crucial and fundamental problem in the robotics field. Therefore, robotics scholars have put a tremendous effort in methods to sense the world through several exteroceptive sensors (e.g., time-of-flight, structured-light, shape from shading, and shape from texture sensors). Using a monocular camera as the primary sensor module, this task constitutes an open challenge for mobile robots operating in indoor environments. Many solutions, which are concerned with the problem of depth estimation, are based on complex deep neural networks. As a result, they remain incompatible with the majority of real-time applications on embedded platforms. Aiming to applications for resource-constrained platforms (including battery-powered aerial, micro-aerial, and ground vehicles), the paper in hand proposes a novel, low complexity network architecture design, dubbed as "PDS-Net", which offers a fast and accurate pedestrian depth estimation and segmentation. Exhaustive experiments on three self-generated datasets prove our network capability to execute in real-time achieving higher frame rates than contemporary state-of-the-art frameworks (114.6 frames per second on an NVIDIA Jetson Nano GPU) while maintaining comparable accuracy.
