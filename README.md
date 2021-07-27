# RollercoasterVR

Rollercoaster model: https://sketchfab.com/3d-models/roller-coaster-06a750a284104d76ba6a05c2b0f5ccf3

Outline shader: https://roystan.net/articles/outline-shader.html

## Switch to VR mode:
- In OculusSampleFrameworkUtil.cs, uncomment [InitializeOnLoadAttribute].
- In hierarchy, RollerCoaster_02 → Dummy008, uncheck CameraView and check OVRCameraRig.

## Switch to editor mode:
- In OculusSampleFrameworkUtil.cs, comment out [InitializeOnLoadAttribute].
- In hierarchy, RollerCoaster_02 → Dummy008, uncheck OVRCameraRig and check CameraView.

## Turn outline shader on / off:
Go to assets → OutlineShader → OutlinePostProfile and check/uncheck Post Process Outline

