# Auto-Annotation-with-a-Camera
# A tool for easy dataset creation. I mean small datasets but who knows :)
Just take images of the objects of interest and you'll get them automatically annotated with pixelwize maps.

How to use it:
To create and automatically annotate datasets.
1. Run Application.
2. Set camera steady with no moving or flickering objects on the scene.
3. Precc "b" button. Camera will take a shot of the scene and later will concidered it a background.
4. Put one or a few objects of the same class on the scene. Do not put objects of different classes on the same csene. 
5. Press "q" button to take a picture of the scene with objects.
   The application wil take a shot and create two png files with images of the scene and a mask.
   The mask image is a diff betveen a background and a an object images.
6. Rrepeat steps 4 and 5 to make more shots. Watch for artifacts on the mask. If the program don't cover objects wit the mask or draws errorneous artefacts try to adjust parameters Kernel and Threshold
7. To create another serie of images with a different background change scene and repeat steps 3-6
8. To exit application press x button
9. To create images of another class objects edit classNum variable and restart application.
