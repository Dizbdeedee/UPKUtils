UPKUtils
========

Set of utilities to work with UPK files


How to compile under Linux:
===========================
Install gcc-c++ (g++) compiler, cmake, git and any wxGTK-devel v.2.9+ package available for your distribution repository. There is one program which requires wxWidgets - DeserializeAll. Everything else should compile perfectly without wxGTK installed.

Clone github repo and compile UPKUtils project:
```
git clone https://github.com/wghost/UPKUtils.git
cd UPKUtils/build
cmake .
make
```
To compile XComLZO packer/unpacker (you don't really need this unless you're trying to mod textures without TexMod):
```
cd UPKUtils/XComLZO/build
cmake .
make
```
