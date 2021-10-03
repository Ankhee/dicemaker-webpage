## DiceMaker quick start guide

Hey, thanks for checking out DiceMaker!

This short tutorial is meant to explain the features of the tool. We'll start a new project, customize a die, and finally export it for your 3D printer.

### Interface

When you first open DiceMaker, you'll see an empty scene with two side panels. Left panel lets you manipulate the whole project - add dice, change project-wide font settings, save, load, export the project, and so on. Right panel lets you change die- or face-specific parameters, like die size, engraving position, custom graphics, and so on.

Let's start by adding the first die to the scene. Select the "Add" button, then select the type of die you wish to add. Here, we've added a D20.

![Image](/assets/img/quick_start_01.png)

You can rotate the view by pressing the middle mouse button (MMB) and moving the mouse, and pan the view by pressing the right mouse button (RMB) and moving the mouse. You can use the mouse wheel to zoom in or out. To reset the camera position, double press the middle or right mouse button. Alternatively, you can hold CTRL on your keyboard to rotate, hold SHIFT to pan, or hold ALT to zoom.

You can select specific dice faces by clicking them with left mouse button (LMB). When a face is selected, you can edit its settings in the right panel.

### Customizing dice

First, let's change the font used throughout the project. To do so, click on the "Default Faces" button in the left panel, then press the "O" button, and load a .ttf font file. We could customize default dice faces further, but for now, let's just save.

Note: variable-width fonts are not supported currently.

![Image](/assets/img/quick_start_02.png)

Saving changes in Default Faces window changes all dice face settings in the project. If we were to add a new die now, it would also use the font we've just selected.

For each face we can change the horizontal and vertical offset of the engraving, as well as its scale and rotation. I want to make the numbers a little bigger, so I'm going to select a face, and increase the scale a bit. Now, we could copy these new parameters to each other face by pressing the "Copy parameters to each face" button, but I'm not going to. Faces 1 through 9, being single-digit numbers as they are, can have relatively bigger numbers than their double-digit counterparts. What I'm going to do instead is click on every other single-digit face while holding down CTRL button - this will copy offset, scale and rotation parameters selectively.

![Image](/assets/img/quick_start_03.gif)

Finally, let's add a custom graphic for the 20 face. Select it, then press the "Load Image" button, and select a .png file. The image should be black and white, with black regions representing egravings on the die. There's a few parameters to tweak for the vectorization process - play with them to achieve the best result, but try to keep the vertex number low. When you're done with the importing, click on the "Finish" button. 

You might need to tweak offset, scale or rotation of the engraving after importing your image.

![Image](/assets/img/quick_start_04.png)

### Exporting the project

To export the dice, simply go to Main Menu -> Export. Select the die you wish to export (or all of them at once), click on the "Export" button, select location, and save. You can open the .stl files in your print preparation software of choice (like Chitubox, Lychee Slicer, etc.), and print your own, custom, unique dice masters.

Happy making!