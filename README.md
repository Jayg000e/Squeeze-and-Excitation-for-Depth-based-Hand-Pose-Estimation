# Squeeze-and-Excitation-for-Depth-based-Hand-Pose-Estimation

  Depth-based hand pose estimation is a computer vision technology with a wide range
of applications. It is an research area with a history of decades. Recently, some researchers try to convert depth images into point clouds, using preprocessingfree point
cloud analysis algorithms that have emerged in recent years to obtain hand pose. These
algorithms usually need to perform complex refinement and nondifferentiable farthest-point-sampling . This thesis introduces the ”squeeze-excitation” module into point cloud
analysis network for depth based hand pose estimation and points out that it can introduce
refinement into the network, so that the refinement module can be added to end-to-end
training. At the same time, we point out that the ”squeeze-excitation” module reserving points is essentially a differentiable sampling operation when a max pooling layer is
inserted. We give a theoretical proof of its important characteristics in the point cloud
analysis network and analyze whether it is complementary to other modules. Finally, we explore performance of our model on the public MSRA dataset.
