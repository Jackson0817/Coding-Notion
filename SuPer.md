For the GS nodes updating, the problem is how to update their location
Update the model through the loss between the rendering result rather than between the GS nodes of the new frame


Right now, the question will be 
1. How do other people solve this issue?
   - They assume the parameter of the GS nodes doesn't change when deforamtion happens other than the point location
   - They have the robot control information, and use it as an input. The dataflow will be

[[TODO]]