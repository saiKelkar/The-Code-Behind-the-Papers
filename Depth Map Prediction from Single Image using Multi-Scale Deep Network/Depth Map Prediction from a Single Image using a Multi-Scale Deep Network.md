Question:
predicting depth of an object from a single image - important for understanding 3D geometry of a scene

Solution:
using two deep network stacks - one that makes a coarse global prediction based on the entire image and another that refines this prediction locally

Globally - cues such as vanishing points, object location, environment setting, etc., is taken into consideration
Locally - cues such as object and wall edges