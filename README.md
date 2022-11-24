# line-detection-dockers

This repository provides adapted and docker-wrapped line segments detection algorithms.
### Structure
Each folder contains an adapted algorithm, a `Dockerfile`, and instructions for building and running.

### Adapted algorithms
The following detectors are currently adapted.


| Name        | Paper | Original implementation                                                                      |
|-------------| --- |----------------------------------------------------------------------------------------------|
| F-Clip      | [Fully Convolutional Line Parsing](https://arxiv.org/abs/2104.11207v2) | [Code](https://github.com/Delay-Xili/F-Clip)                                                 |
| HAWP        | [Holistically-Attracted Wireframe Parsing: From Supervised to Self-Supervised Learning](https://arxiv.org/abs/2210.12971) | [Code](https://github.com/cherubicXN/hawp)                                                   |
| L-CNN       | [End-to-End Wireframe Parsing](https://arxiv.org/abs/1905.03246) | [Code](https://github.com/zhou13/lcnn)                                                       |
| HT-LCNN     | [Deep Hough-Transform Line Priors](https://arxiv.org/abs/2007.09493) | [Code](https://github.com/yanconglin/Deep-Hough-Transform-Line-Priors)                       |
| TP-LSD      | [TP-LSD: Tri-Points Based Line Segment Detector](https://arxiv.org/abs/2009.05505) | [Code](https://github.com/Siyuada7/TP-LSD)                                                   |
| ULSD        | [ULSD: Unified Line Segment Detection across Pinhole, Fisheye, and Spherical Cameras](https://arxiv.org/abs/2011.03174) | [Code](https://github.com/lh9171338/Unified-Line-Segment-Detection)                          |
| LETR        | [Line Segment Detection Using Transformers without Edges](https://arxiv.org/abs/2101.01909) | [Code](https://github.com/mlpc-ucsd/LETR)                                                    |
| M-LSD       | [Towards Light-weight and Real-time Line Segment Detection](https://arxiv.org/abs/2106.00186) | [Code](https://github.com/navervision/mlsd)                                                  |
| AFM         | [Learning Attraction Field Representation for Robust Line Segment Detection](https://arxiv.org/abs/1812.02122) | [Code](https://github.com/cherubicXN/afm_cvpr2019)                                           |
| LSDNet      | [LSDNet: Trainable Modification of LSD Algorithm for Real-Time Line Segment Detection](https://arxiv.org/abs/2209.04642) | [Code](https://github.com/iitpvisionlab/LSDNet)                                              |
| LSD         | [LSD: A Fast Line Segment Detector with a False Detection Control](https://ieeexplore.ieee.org/abstract/document/4731268) | [OpenCV](https://docs.opencv.org/3.4/d1/dbd/classcv_1_1line__descriptor_1_1LSDDetector.html) |
| Cannylines  | [Cannylines: A parameter-free line segment detector](https://xiaohulugo.github.io/papers/CannyLine_Line_Detection_ICIP2015.pdf) | [Code](https://github.com/ludlows/CannyLine)                                                 |
| HoughLines  | [Use of the Hough transformation to detect lines and curves in pictures](https://dl.acm.org/doi/pdf/10.1145/361237.361242) | [OpenCV](https://docs.opencv.org/3.4/dd/d1a/group__imgproc__feature.html#ga46b4e588934f6c8dfd509cc6e0e4545a)                                               |
| HoughLinesP | [Robust Detection of Lines Using the Progressive Probabilistic Hough Transform](https://www.sciencedirect.com/science/article/abs/pii/S1077314299908317) | [OpenCV](https://docs.opencv.org/3.4/dd/d1a/group__imgproc__feature.html#ga8618180a5948286384e3b7ca02f6feeb)                                               |
| Edlines | [Edlines: A real-time line segment detector with a false detection control](https://www.researchgate.net/profile/Cihan-Topal/publication/220644982_EDLines_A_real-time_line_segment_detector_with_a_false_detection_control/links/61069f68169a1a0103cd2a9a/EDLines-A-real-time-line-segment-detector-with-a-false-detection-control.pdf7) | [OpenCV](https://docs.opencv.org/3.4/d4/d8b/group__ximgproc__edge__drawing.html)                                               |