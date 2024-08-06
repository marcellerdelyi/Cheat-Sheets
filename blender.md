# Blender
## Running external Blender python scripts

- Navigate to the directory where the script is saved.
- Run the script with Blender in the background (silent mode):

```ps
& "BlenderFoundaition\stable\blender1.1.1.1\blender.exe" --background --python "Path\to\blender\script\BlenderScript.py"
```
- & is the call operator in PowerShell that allows you to run commands and scripts or executables, especially when their paths contain spaces or special characters that would otherwise cause syntax issues..
- The full path to blender.exe is provided in quotes to handle any spaces in the path.

```cmd
blender -b -P BlenderScript.py -- Path\to\fbx\location
```
> [!NOTE]  
> - for testing purposes just move the python script right under neath the location where the blender executable file is.