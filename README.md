# OC-Blender-Helper-Addon

A helper addon for Octane Blender edition



> I developed this addon for speeding up user workflow, so users can access powerful functions provided by Octane and AI to make their projects, and newcomers can know where to start

> I welcome issue reports, please let me know where to promote and fix

> Glhf



## Versions

* **OctaneRender™ for Blender XXX and later**
* Current version **v3.0.0**
  * Tested on **Blender_Octane_Edition_XXX**
  * Developed on **Electron**, **NodeJS**, **AngularJS**, **TypeScript**, **Tensorflow**, **Blender**

## Installation 

* Go to [Releases](https://github.com/Yichen-Dou/OC-Blender-Helper-Addon/releases)
* Download the newest **Octane_Helper_[Platform].zip**
* Blender Preferences > Add-ons > Install
* Select **Octane_Helper_[Platform].zip** to install
  * Please do not install the zip from the downloaded repository named OC-Blender-Helper-Addon-master.zip. If you are interested in developing new features, you have to compile it for your target platform
* Activate it
  * If you have installed the addon before, please restart your Blender

## Features

**Octane Helper GUI**

XXX

**Right-Click Menus**

XXX

**Megascans Module**

* **Since v3.0.0, the Megascans module no longer listens to the Bridge App. Instead, megascans assets can be automatically detected by Octane Helper, and you can locate them in Assets library alongside with any other asset you have**
  * This means, do not click the Export button in the Bridge App. You just need to download them and use them in Octane Helper's Assets Library :) 
* The imported surface material can be found in Material Slots
  * It will not automatically  be applied to selected objects
  * You can also use Right-Click menu > Paste Material to paste the surface material to selected

![image-20200308174856061](assets/image-20200308174856061.png)

![image-20200308175602574](assets/image-20200308175602574.png)

![image-20200613123137705](assets/image-20200613123137705.png)

**Minimum textures to get a correct response for Megascans Module**

![image-20200308173100845](assets/image-20200308173100845.png)

**Supported Textures for Megascans Module**

| Textures         | Info                             |
| ---------------- | -------------------------------- |
| **Albedo**       | Added by default (If exists)     |
| **Displacement** | Added by default (If exists)     |
| **Normal**       | Added by default (If exists)     |
| **Roughness**    | Added by default (If exists)     |
| **Specular**     | Added by default (If exists)     |
| Opacity          | Added by default (If exists)     |
| Translucency     | Added by default (If exists)     |
| Metalness        | Added by default (If exists)     |
| AO               | Added by default (If exists)     |
| Bump             | Optional (Toggle in preferences) |
| Fuzz             | Optional (Toggle in preferences) |
| Cavity           | Optional (Toggle in preferences) |
| Curvature        | Optional (Toggle in preferences) |

## Questions

* Other issues
  * Please check out the log from Blender > Top Bar > Window > Toggle System Console and let me know what's happening

