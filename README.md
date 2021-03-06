# PPV_Volumes
PPV Volume is an addon for Armory3D that implements volumes that controls or triggers changes
of the values provided to the shaders in Armory.
This allows for interactive color grading
For now, there's only one global volume that can be changed. This will be changed in the version 0.2.

## Why as an addon?
I'd rather not commit something to Armory that is still bugged and not as optimized as possible. Still lots of things to do to make it useful. This is compatible with the Armory 0.2 version - This addon might break Armory. Bugs should be reported on this github section rather than the main Armory repo.


## How to
Simply copy and paste the **armsdk** folder directly into your Armory/Blender main folder and it will expose and implement the controls straight away.

- Open up blender and make a quick scene with a camera.
- In the render tab, make sure ZUI is set to **enabled**.
- Go to the object tab and make a new haxe script
- Name it "**PPV_Volume**"
- Copy & Paste the "**Sources**" folder into your project

If you run your project now, you should now have a sidebar that will allow you to modify the various postprocess values.

## To do:
- Add controls and make transitions working
- Implement controls for Bloom, Vignette, Film Grain and more.
- Add load/save functions for preset files Blender and Krom
- Pictures to explain the how to.