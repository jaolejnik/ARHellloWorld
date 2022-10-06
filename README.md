# AR Hello World [MAMN60]

An implementation of a simple Android AR app using Unreal Engine's 5 **Handheld AR Template**. 

## Functionality
- Use the SLAM algorith to detect a surface and place an interactable animated 3D model.
- Detect pre-configured images and place an animated 3D model on top of them.

## What has been done
- Imported custom FBX models with skeletons and animations
- Replaced default static mesh in `BP_Placeble` blueprint with custom skeletal mesh
- From `BP_Placeable` created child blueprint, `BP_Imageable` for placing models on images
- Configured `D_ARSessionConfig` to support image detection
- Added additional sequence in `BP_ARPawn for image detection with the following blueprint nodes:
https://blueprintue.com/blueprint/qsn0p3oc/

## Sources:
- [Handheld AR Template Quickstart](https://docs.unrealengine.com/4.26/en-US/SharingAndReleasing/XRDevelopment/AR/HandheldAR/ARQuickStart/)
- [UE4 27 ARCORE IMAGE TUTORIAL by Enrico Costi](https://youtu.be/BP9hjnMFRRM)
