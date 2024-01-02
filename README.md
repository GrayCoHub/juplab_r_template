A Dockerfile repo.


The original Dockerfile, re-named Dockerfile_original, will create a Docker Image and Container running a Jupyter Lab notebook.  
This Dockerfile will start the Jupyter Lab server and launch a browser pointed to the Jupyter Lab Launcher website.  

Various changes to the Dockerfile CMD were made in order to get the docker container to succesfully work. The most recent commit 
of the Dockerfile is the starting point used for this repo.  
This current Dockerfile in the repo named main pulls the base images of python and base R from the Docker Hub and builds a image 
of Jup Lab using the R kernel.  This build is streamlined and only uses those libraries and packages necessary to build a 
Jupyter Lab notebook using the R kernel.  

This Dockerfile will successfully build a Docker image of the Jupyter Lab
notebook.  A Container will successfully start the Jupyter Lab notebook at the first cell in the notebook. 

 Goal: to open a dockerized Jupyter Lab notebook that includes using the code from the gcode notebook.  Hopefuelly a this 
 dockerized version of the gcode notebook can be created without involving the process of copying / pasting the code from the gcode 
 notebook into an empty notebook happening within the dockerfile - basically meaning creating a Jupyter notebook similar to a base image. 
