## Welcome to SKetchFabShowAndHide 

# Custom viewer for Sketfab utilizing the Viewer API to allow showing and hiding of the model's parts

Caecilia tentaculata: https://croisened.github.io/SketchFabShowAndHide/?id=5fe064bac9914e33a84f1c5f2007de1b
Rhinatrema bivittatum: https://croisened.github.io/SketchFabShowAndHide/?id=be5c11d602b84de393ee2eb26455ba6c


To use this project you only need 3 files...

- index.html (This file just has the HTML scaffolding to house the Sketchfab API viewer)
- style.css (This file contains the bootstrap based layout information)
- sf_showhide.js (This file contains all the code to initialize the Sketchfab viewer, process all the Matrix Transforms and ultimatley generate the treeview with show and hide buttons for each object in the scene)

In the javascript file there is an "id" variable that you can change to be any model on Sketchfab based on that model's guid you can see in the URL for any given model.  This acts as default model to load in the event there is no "id" variable set in the querystring for the HTML page so you can simply chage it there as well to view any model you choose.

Follow on Twitter @FullyCroisened
