# Audio-Modding-Template
This is a template UE project for audio modding. 

All of the assets are reconstructed from the unpacked asset data meaning that they have the same properties as the original assets. 

Use is as simple as downloading Unreal Engine 4.27 and opening the `Hk_project.uproject`!

Thanks to `LongerWarrior` for writing the `Cooked Asset Serializer` tool that allows us to reconstruct the assets, and `Archengius` for creating the `UEAssetToolkit` plugin that generates the assets inside the project.

## Main branch
Most audio modders will want to use the template project on this branch. This does not include the sound cues and sound waves, but includes everything else. It means that you just use the assets in this project for references.

## All-assets branch
This branch contains all of the audio assets - so those in main branch plus sound cues (with graphs so that they are fully functional) and sound waves. Simply copy the Content folder and paste it into the Hk_project from the main branch, overwriting any files when prompted.
