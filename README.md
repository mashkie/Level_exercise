# Game Engineering - Exercise 2

The level can be found in the scenes folder inside the Assets folder.  
There are two scenes:

* The test scene only contains the blender asset
* The Map_Hosp1 contains the level with the blender asset inserted

## 3rd Party Assets

Besides the blender asset `medkit_v2` (which can be found in the Medkit folder) all other assets were taken from the
unity asset store.

* The hospital level is taken from
  the [PBR - Hospital Horror Pack](https://assetstore.unity.com/packages/3d/environments/pbr-hospital-horror-pack-free-80117)
* The player is taken
  from [Free Test Character Asuna](https://assetstore.unity.com/packages/3d/characters/humanoids/sci-fi/free-test-character-asuna-205897)

## Trouble shooting

The project was created with the 3D URP template. There it happened that all shaders of the 3rd party assets were broken
and displayed in pink.  
To fix this the material had to be converted with help of the URP pipeline. To do this move to
`Window -> Rendering -> Render Pipeline Converter` and select all checkboxes and click `Initialize And Convert`

