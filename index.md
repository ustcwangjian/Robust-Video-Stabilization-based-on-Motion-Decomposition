<h1 align="center">Abstract</h1>

<div align="justify">Video stabilization aims to smooth out unwanted video shakiness. Traditional video stabilization methods are usually based on either background feature trajectories or all feature trajectories.
The methods of background trajectories make use of only a part of trajectories and may yield serious distortion in the foreground regions due to the insufficient number of background trajectories. 
The other methods take all feature trajectories into account and smooth all trajectories to generate their stabilized views. However, the goal of video stabilization is to stabilize the camera jitter which is consistent with the jitter of only background trajectories, and smoothing foreground trajectories could yield unnecessary distortion. 
To address the above issues, this paper firstly proposes a trajectory clustering algorithm, then makes use of all trajectories to perform content-preserving warping and mainly smooths background trajectories by assigning larger smoothing weights to them.
When the camera is moving, the trajectory smoothing constraint, which enforces the corresponding feature points of consecutive frames to stay at the same position, may lead to video frame collapse and over-smoothing of stabilized videos. To solve this problem, this paper proposes a sliding window camera motion estimation method that considers the correlation of motion direction between consecutive frames. 
By reducing the weight of the above trajectory smoothing constraint according to the estimated camera motion, we can well avoid video frame collapse and over-smoothing of stabilized videos.
At the same time, we adopt a trajectory selection strategy to ensure the even distribution of feature trajectories and reduce the number of variables, which helps to enhance the stabilization performance and reduce the computational burdens. 
Experiments demonstrate the robustness and effectiveness of our video stabilization method through a variety of challenging videos.</div>

<h3>Comparsion with adaptively and effective</h3>
<a href="https://raw.githubusercontent.com/ustcwangjian/Robust-Video-Stabilization-Based-On-Trajectory-Weighting-and-Motion-aware-Trajectory-Smoothing/gh-pages/example_1.mp4">example_1.mp4</a>

<h3>Comparsion with global and meshflow</h3>
<a href="https://raw.githubusercontent.com/ustcwangjian/Robust-Video-Stabilization-Based-On-Trajectory-Weighting-and-Motion-aware-Trajectory-Smoothing/gh-pages/example_2.mp4">example_2.mp4</a>

<h3>Comparsion with bundled and deep learning</h3>
<a href="https://raw.githubusercontent.com/ustcwangjian/Robust-Video-Stabilization-Based-On-Trajectory-Weighting-and-Motion-aware-Trajectory-Smoothing/gh-pages/example_3.mp4">example_3.mp4</a>

<h1 align="center">Reference</h1>
<div align="justify">[1] S. Liu, L. Yuan, P. Tan, and J. Sun, “Bundled camera paths for video stabilization,” in ACM Trans. Graph., vol. 32, no. 4, Jul. 2013.</div>  
<div align="justify">[2] L. Zhang, Q.-K. Xu, and H. Huang, “A global approach to fast video stabilization,” in IEEE Transactions on Circuits and Systems for Video Technology, vol. 27, no. 2, 2015, pp. 225–235.</div>
<div align="justify">[3] T. Ma, Y. Nie, Q. Zhang, Z. Zhang, H. Sun, and G. Li, “Effective video stabilization via joint trajectory smoothing and frame warping,” in IEEE Transactions on Visualization and Computer Graphics, 2019.</div>       
<div align="justify">[4] M. Zhao and Q. Ling, “Adaptively meshed video stabilization,” in IEEE Transactions on Circuits and Systems for Video Technology, 2020, pp. 1–1. </div>   
<div align="justify">[5] M. Zhao and Q. Ling, “Pwstablenet: Learning pixel-wise warping maps for video stabilization,” in IEEE Transactions on Image Processing, vol. 29, pp. 3582–3595, 2020. </div>  
<div align="justify">[6] S. Liu, P. Tan, L. Yuan, J. Sun, and B. Zeng, “Meshflow: Minimum latency online video stabilization,” in European Conference on Computer Vision. Springer, 2016, pp. 800–815.</div>

