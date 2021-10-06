# Open 3D Engine (O3DE) Tutorial Assets Gem

The Tutorial Assets Gem contains models, textures, animation, and so on, used in O3DE tutorial docs and videos.

This Gem is a community Gem that accepts asset contributions provided that all submissions are the original work of the submitter, or the submitter has the rights to distribute the assets in this open source repository under the MIT and Apache 2.0 licenses.

## Installation

1. Clone the repository, or download the archive.
1. Copy the `TutorialAssets` directory to you o3de/Gems directory.
1. Edit `o3de/engine.json`, and add `"Gems/TutorialAssets"` to the `"external_subdirectories":` list.
1. Rebuild O3DE.
1. In **Project Manager** add the Tutorial Assets Gem to your project.
1. Rebuild your project.

The assets can be found in the `<o3de engine>/Gems/TutorialAssets` directory in **Asset Browser**.

## Submission Guidelines

* All asset submissions must be distributable under the MIT and Apache 2.0 licenses.
* Optimize all files before submission. Ensure no file is larger than it needs to be.
* Only sumit files required by the asset.
* Keep asset files organized in their own directories.
* Meshes should be a reasonable resolution for their use case. There are no strict limits, however, be mindful of file size bloat in the repository.
* The inclusion of Blender (`.blend`) source files is highly encouraged. Do not include proprietary scene files from closed source apllications (`.ma`, `.max`, `.psd`, and the like) unless the tutorial *requires* the features of closed source applications.
* Images and textures should be no larger than 2048 pixels square, and should be in `.png` format, unless required in the context of the tutorial. Terrain heighmaps and HDR image maps, for example may require more resolution and specialized formats.