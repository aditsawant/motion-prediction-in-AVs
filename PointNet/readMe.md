# Motion Prediction with PointNet
We have used the PointNet Architecture to predict the motion of AVs.
For this problem statement, the general approach for data representation is *Rasterization*. The main advantage of using PointNet architecture is that it works directly on the agents dataset.<br>
Having no GPU access, we were able to achieve a decent accuracy by training the model for about 8 hours only. <br>

The PointNet model uses a combination of feed-forward (conv1d) models along with some transformation matrices and symmetric functions (max pooling) to deal with unordered set of points (agents).
To get a basic idea about PointNet, you should watch their original presentation [video](https://www.youtube.com/watch?v=Cge-hot0Oc0) in CVPR '17. <br>
Or you could refer:
- [Main webpage](https://stanford.edu/~rqi/pointnet/)
- [GitHub repo](https://github.com/charlesq34/pointnet)
- [Original paper](http://arxiv.org/abs/1612.00593)
