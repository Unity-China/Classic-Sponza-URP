# Classic Sponza - Universal Render Pipeline

## Information

This repository is altered version for Unity new feature [Adaptive Probe Volumes (APV)](https://portal.productboard.com/unity/1-unity-platform-rendering-visual-effects/c/2048-adaptive-probe-volumes-apv-urp) from project of Unity [Classic Sponza](https://github.com/Unity-Technologies/Classic-Sponza) repository page.

![Sponza-APV](ClassicSponza_UnityRemaster.jpg)

#### YouTube Video Tutorial: [Lighting tutorial: 4 techniques to light environments in Unity | Unite 2022](https://www.youtube.com/watch?v=DlxuvvYZO4Q&t=922s)

## Summary

The Atrium Sponza Palace scene is widely used by graphics programmers and artists. It provides with an ideal lighting test environment, as it features both indoor and outdoor areas. 

The goal of this conversion was to modernize the project in key areas, making it compliant with modern rendering standards.

### Features

- Full compatibility with Unity's Universal Render Pipelines.
- All textures and materials are PBR-compliant.
- Physical lighting and exposure.
- Baked Indirect lighting using the Adaptive Probe Volumes (APV).

## Requirements

Unity Editor 2023.1.0b13 or Newer

## Setup

### Cloning the project

#### Important note
This project makes use of [Git Large Files Support (LFS)](https://git-lfs.github.com). You need to install LFS on your local machine first. **Do not download the project via the Download ZIP option.** Once you have installed LFS, please follow the steps outlined below.

#### Using the GitHub Desktop client
Click on the green Code button at the top, and select *Open in Desktop* option.

#### Using alternative git clients
Paste the following web URL into your preferred git client: `https://github.com/Unity-China/Classic-Sponza-URP`.

#### Using command line or terminal
Open your preferred command line application and enter the following command: `git clone https://github.com/Unity-China/Classic-Sponza-URP`.

### Setting up the project in Unity
This project makes use of multi-scene workflow. In order to make sure that everything works as expected, please follow these steps:
1. In the **Project** tab, navigate to **Assets > _APV **.
2. Open **Sponza-APV** scene.
3. Once it finishes loading, right-click on the **SponzaLightingAPV** scene and select the **Open Scene Additive** option.
4. In the **Hierarchy** panel, right-click on the SponzaLightingAPV scene, and select the **Set Active Scene** option.

Note that the initial shader compilation stage might take some time. There is a chance that nothing might be visible in the viewport before its completion.

## Credits

- Sponza model authored by Frank Meinl at [Crytek](https://www.crytek.com/).
- Sponza model acquired from [McGuire Computer Graphics Archive](https://casual-effects.com/data/).
- HDRI acquired from [NoEmotion HDRs](http://noemotionhdrs.net/).
- Unity conversion carried out by [Kristijonas Jalnionis](https://github.com/radishface).
- Special thanks to [Kemal Akay](https://github.com/kemalakay) and [Laurent Harduin](https://github.com/laurenth-personal) for their assistance with the initial project setup.
