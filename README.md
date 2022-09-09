# FileManager

This FileManager was created for *Webtronics* how test task.

## Realized ##
Functional requirements:
- Consists of a single area *("working area")*, which displays the contents of the current directory (or folder)
- Upon double clicking on an element:
  - If it is a *file*, then the application tries to open using windows;
  - If it is a *folder*, then the working area is filled with the contents of this *folder*
- Upon a single click on an element, on the right side of the working area, a panel should appear that displays *additional information*:
  - If it is a *file*, then its metadata is displayed *(size, date created, etc..)*
  - If it is a *folder*, then its size and amount of file it contains is displayed
- Upon opening a *file*, write into the database. The history entity contains:
  - Id
  - Filename
  - Date visited
  
## How open this program ##
**Some steps**:
- At first you need to realize script, where describe creating database *(file: createdb.sql)*
- After this you can open program *(/Debug/FileManager.exe)*

**That's all!**

![image](https://user-images.githubusercontent.com/68136994/189360325-70a84cf8-9764-4832-b13b-2b0705e1a44f.png)


