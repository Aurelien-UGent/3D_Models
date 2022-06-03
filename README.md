## The anatomy of the head muscles in caecilians (Amphibia: Gymnophiona): variation in relation to phylogeny and ecology? 

# 3D reconstructions of caecilians cephalic musculature

_Caecilia tentaculata_: https://croisened.github.io/SketchFabShowAndHide/?id=5fe064bac9914e33a84f1c5f2007de1b

_Rhinatrema bivittatum_: https://croisened.github.io/SketchFabShowAndHide/?id=8d4835ea0db64d2dbd69f7f82b23a524


# Modified script from FullyCroisened
# Custom viewer for Sketfab utilizing the Viewer API to allow showing and hiding of the model's parts
To use this project you only need 3 files...

- index.html (This file just has the HTML scaffolding to house the Sketchfab API viewer)
- style.css (This file contains the bootstrap based layout information)
- sf_showhide.js (This file contains all the code to initialize the Sketchfab viewer, process all the Matrix Transforms and ultimatley generate the treeview with show and hide buttons for each object in the scene)

In the javascript file there is an "id" variable that you can change to be any model on Sketchfab based on that model's guid you can see in the URL for any given model.  This acts as default model to load in the event there is no "id" variable set in the querystring for the HTML page so you can simply chage it there as well to view any model you choose.

Follow on Twitter @FullyCroisened
