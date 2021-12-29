<h1 align="center">Abstract</h1>

<div align="justify">Video stabilization aims to eliminate the camera jitter and improve the visual experience of shaky videos. The previous video stabilization methods ignore the active movement of the foreground objects and the camera, and may result in distortion and over-smoothing problems. To resolve these issues, this paper presents a novel video stabilization method based on motion decomposition. Since the inter-frame movement of foreground objects is different from that of background, we first separate foreground feature points from background feature points by modifying the classic density based spatial clustering method of applications with noise (DBSCAN). The movement of background feature points is consistent with the movement of the camera, and can be decomposed into the camera jitter and the active movement of the camera. And the movement of foreground feature points can be decomposed into and the movement of the camera and the active movement of foreground objects. Based on motion decomposition, we design first-order and second-order trajectory smoothing constraints to eliminate the high-frequency and low-frequency jitter of the camera. To reduce content distortion, shape-preserving constraints and regularization constraints are taken to generate the stabilized view of all feature points.  
Experimental results demonstrate the effectiveness and robustness of the proposed video stabilization method on a variety of challenging videos.</div>

<h3>Validation of the iterative DBSCAN feature point clustering.</h3>
<a href="https://raw.githubusercontent.com/ustcwangjian/Robust-Video-Stabilization-based-on-Motion-Decomposition/gh-pages/clustering.mp4">clustering.mp4</a>

<h3>Comparsion with previous video stabilization method.</h3>
<a href="https://raw.githubusercontent.com/ustcwangjian/Robust-Video-Stabilization-based-on-Motion-Decomposition/gh-pages/comparison.mp4">comparison.mp4</a>

<h1 align="center">Reference</h1>
<div align="justify">[1] S. Liu, L. Yuan, P. Tan, and J. Sun, “Bundled camera paths for video stabilization,” in ACM Trans. Graph., vol. 32, no. 4, Jul. 2013.</div>  
<div align="justify">[2] L. Zhang, Q.-K. Xu, and H. Huang, “A global approach to fast video stabilization,” in IEEE Transactions on Circuits and Systems for Video Technology, vol. 27, no. 2, 2015, pp. 225–235.</div>
<div align="justify">[3] T. Ma, Y. Nie, Q. Zhang, Z. Zhang, H. Sun, and G. Li, “Effective video stabilization via joint trajectory smoothing and frame warping,” in IEEE Transactions on Visualization and Computer Graphics, 2019.</div>       
<div align="justify">[4] M. Zhao and Q. Ling, “Adaptively meshed video stabilization,” in IEEE Transactions on Circuits and Systems for Video Technology, 2020, pp. 1–1. </div>   
<div align="justify">[5] M. Zhao and Q. Ling, “Pwstablenet: Learning pixel-wise warping maps for video stabilization,” in IEEE Transactions on Image Processing, vol. 29, pp. 3582–3595, 2020. </div>  
<div align="justify">[6] S. Liu, P. Tan, L. Yuan, J. Sun, and B. Zeng, “Meshflow: Minimum latency online video stabilization,” in European Conference on Computer Vision. Springer, 2016, pp. 800–815.</div>
<div align="justify">[7] Y. J. Koh, C. Lee, and C. Kim, “Video stabilization based on feature trajectory augmentation and selection and robust mesh grid warping,” IEEE Transactions on Image Processing, vol. 24, no. 12, 2015, pp. 5260–5273.</div>
