# AssimpImporter
AssimpImporter
Supported file formats
.fbx,.3ds,.obj,.dae,.ifc,.glb,.gltf,.stl,.raw,.q3d...40+
mor format is here
https://github.com/assimp/assimp/blob/master/doc/Fileformats.md


test modelfile
https://github.com/assimp/assimp-mdb

step
1.compile assimp c++ dll
https://github.com/assimp/assimp
this version is 5.25.2

2.add assimp.net C# dll
https://www.nuget.org/packages/AssimpNet/5.0.0-beta1
https://bitbucket.org/Starnick/assimpnet/src/master/

3.**in Unity parser model format**

4.**codeding unity texture,unity mesh,unity material, unity gameobject**

5.generate gameobject and tree

# DatasmithImporter
support OldVersion 4.26~5.0.3
support NewVersion 5.1.1~5.4.x

can self extend to runtime

drag  .udatasmith fileand assets folder to Project/Assets folder


# SketchUPImporter

1.invoke sketchup sdk in c# wrapper
2.parse skp file
3.unity mesh material,game object and tree

Update Sketchup version
change(replace) dll in Sketchup 2024
thanks! https://github.com/moethu/SketchUpNET
