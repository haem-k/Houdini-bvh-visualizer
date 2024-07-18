# Houdini-bvh-visualizer
Visualize bvh file with Houdini
Character model is set to YBot in mixamo
Used Houdini version 19.5.626

## How to use
* Find _visualize (Mocap Import) node_ and _rest_pose (Mocap Import) node_
* Drag and drop bvh file to 'BioVision Motion Capture File' field
* Visualize the last _jointdeform1 node_

## Custom character
* Find _fbxcharacterimport1 node_
* Drag and drop fbx file to 'FBX File' field
* Match the skeletons with _rigmatchpose1 node_
* Create mapping between joints with _mappoints2 node_
* Visualize the last _jointdeform1 node_

## Reference
<https://www.sidefx.com/docs/houdini/character/kinefx/motioncapture.html>    
<https://www.sidefx.com/tutorials/retarget-the-cmu-motion-capture-database-19_5/>    
<https://youtu.be/66dCN0sg2D4?feature=shared>
