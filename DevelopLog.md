Jan 26, 2016

1. Export point clouds data to be *.pts: Uploaded on [Google Drive]().
2. Paper research: [Position Based Fluid, 2012 Nvidia](http://mmacklin.com/pbf_sig_preprint.pdf) Will implement this for fluid.

Note:

  1. The exported *.pts file takes 8Gb, which is infeasible to load. Need to start with smaller model
  2. Need to study on how to deal with collision. 
  3. Implement the mass spring simulation next week

Feb 3, 2016

1. Downsampled point clouds to 80 MB
2. Include GUI feature
3. Mass spring not implemented yet...

Feb  14, 2016

1. Add console and parameter GUI

Feb 21, 2016

1. Integrate FMOD to XRSound, XRSoundManager
2. Integrate Tinyobj loader


Feb 28, 2016

1. Add sound effect
2. Wire up position front up attributes into XRSoundManager for 3D sound rendering

Mar 3, 2016

1. Integrate Oculus SDK

Mar 6, 2016

1. Wired up the Oculus SDK, new branch
2. Regenerate 1/10 resolution of pointcloud for demo

Mar 8-9, 2016

  some feedback from Real2016:

1. The controller cannot move in vertical direction.
2. THe object cannot manipulate.
3. Frame rate is good!
4. Add caption/instruction in the scene would be better.

**Spring Break - moving forward to next stage "City Flood!"**

Apr 1, 2016

1. Add SpatialMap to acclerate neiborhood particles finding

Apr 8, 2016

1. Working on marching cube.

Apr 13. 2016

class note:

As suggested in the class, the fluid simulation could be used as design tool to predict the fluid dynamic in the sink. 
We decided to change the goal from City Flood to the sinker design.

So our next job is to implment the **collision handler** and **mesh modifier** to enable adjust the vercies during the runtime.

Apr 17, 2016

1. Fix marching cube and optimize algorithm to prevent duplicate computation on the same grid.
2. Implement Spatial Grid.

May 1, 2016

1. Implemented height field, normal computed by obj file.
2. Implemented collision handler.

