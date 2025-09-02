# AR-marker

1. Create a Universal 3D Core project
2. Go to Package Manager and Unity Register
3. Install AR Foundation
4. Install Google ARCore XR Plugin
5. Install Apple ARKit XR Plugin

Now you can create a new scene or use the SampleScene
1. Delete the main camera
2. Add a new component XR -> XR origin
3. Add a new component XR -> XR session
4. Go to Edit -> Project Settings
5. Go to Graphics section, click on Default Render Pipeline and it will take you to the place in the project
6. Select PC_Render and Add -> AR Background Render Feature
7. Do the same for mobile renderer
8. Go to XR Plugin Manager
9. Select android and choose Google ARCore, do the same for Apple and its Apple ARkit.
10. Select required in the specific scenes.
11. 