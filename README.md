![DitherFade](https://github.com/user-attachments/assets/b596c586-0fbe-413c-8721-7d74170ead0d)

# Dither Fading Shader Effect
![Unity Version](https://img.shields.io/badge/Unity-2021.3%35LTS%2B-blueviolet?logo=unity)
![Unity Pipeline Support (Built-In)](https://img.shields.io/badge/BiRP_✔️-darkgreen?logo=unity)
![Unity Pipeline Support (URP)](https://img.shields.io/badge/URP_✔️-blue?logo=unity)
![Unity Pipeline Support (HDRP)](https://img.shields.io/badge/HDRP_✔️-darkred?logo=unity)
 
A very simple dither fading shader effect that uses dithering to fade in and out based on camera distance. It was created for Serious Point Games as 
part of my studies in shader development. It is meant to be for Unity URP (2019.3.35f1) but it can work in other unity versions (like Unity 6 or Unity 2022)
and other pipelines (like Built-In). This repo is meant to be a reliable and accessible resource to create the simple dither fading effect.

This is very simple to implement and intergrate to any material shader effect. But if your effect does need to depend on alpha & alpha clipping for
other uses, you will need to find a way to blend the dither fading with whatever effect that relies on alpha & alpha clipping. This repo is to
provide a reliable and accessible means to create the simple dither fading.

You can refer to the effect's documentation for more info (should be in the repo and its release as a PDF file).

## Features
- Dither fade in or out based on camera distance

## Example[s]
![DitherFade](https://github.com/user-attachments/assets/b596c586-0fbe-413c-8721-7d74170ead0d)
<br>
The dither fading shader effect in action

## Installation
1. Clone repo or download the folder and load it into an unity project.
2. Create a new material from the shadergraph, or use the provided one if you want to.
3. Drag the material onto the mesh object/gameobject that you want to apply the effect on, or go to the object’s inspector panel
and change its material to the material with the volumetric spotlight shader.
4. Optionally, you can use one of the prefabs to have a volumetric spotlight by going to the prefab folder and drag one of them into the scene.

## Credits/Assets used
Shader code is based on PabloMakes’ Dither Fade in Unity YouTube video
[Youtube Video Link](https://www.youtube.com/watch?v=rVeS7oh3oug).

