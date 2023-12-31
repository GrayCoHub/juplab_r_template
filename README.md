A Dockerfile repo.


The original Dockerfile, named Dockerfile_original, will create a Docker Image and Container running a Jupyter Lab notebook.  
This Dockerfile will start the Jupyter Lab server and launch a browser pointed to the Jupyter Lab Launcher website.  

Changes to the Dockerfile CMD were made, and the currert Dockerfile is the starting point used for this repo.  This
Dockerfile uses a base python and base R application.  Using only those libraries and packages necessary to build a 
Jupyter Lab notebook with the R kernel.  This Dockerfile will successfully build a Docker image of the Jupyter Lab
notebook.  A Container will successfully start the Jupyter Lab notebook at the first cell in the notebook. 

 Goal: to open the Jupyter Lab notebook using the code from the gcode notebook ... a dockerized version of the gcode notebook.
