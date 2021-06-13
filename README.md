# WaterFlow

## Docs

"Water Flow For UDK.pdf" – tutorial document.


## UE3 files

Created with February 2013 UDK BETA2
 - FlowTest.udk – UDK example map.
 - BaseFlowMaterials.upk – package with all basic materials and textures.


## Houdini files

Created with Houdini FX 18.0.566
 - CombExample.hip – example of Comb tool.
 - ForcesExample.hip – example of forces effects.
 - CurvesExample.hip – example of creating flow using curves.
 - TestMap.hip – big flow setup.
 - Waves.hip – example of creating noise map for phase offset and creating waves with Houdini Ocean Toolkit.
		(needs Houdini Ocean Toolkit -	http://code.google.com/p/houdini-ocean-toolkit/
										https://github.com/eloop/hot
										http://schnellhammer.net/blog/2012/03/hot12/)

Import folder with .obj geometry files needed for "TestMap.hip" scene.
Import folder was in C:\Temp, and Houdini saved that paths in imported geometry nodes.
So, if you place it somewhere else, Houdini will lost that files.
To fix that, open FlowTest_World/*Water/*Waterfall nodes, select inner "File" node and specify new paths in "Geometry File" field.