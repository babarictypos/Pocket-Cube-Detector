#Pocket Cube Detection Deployment
This repository deploys my neural network trained in fastai (v2.x) onto Render as a website. 
#Link
https://pocketcube.onrender.com
Please allow a minute for the webpage to open - I am currently on the free package of Render.
#Creation of Neural Network
Please see my other repository: WIP
I collected approximately 1000 photos of my 2x2x2 Rubix Cube in various angles, lighting and camera specs. 

#Use as a template
This reposistory can also be used as a template for deploying fastai (v2) neural networks (pkl files) onto the cloud service Render. This is adapted from Render's repo for Fastaiv1 deployment. Note they state it is for for fastai v3 where the version applies to the course version, not library.

Forked from https://github.com/render-examples/fastai-v3

CHANGES: The deployment in original was designed for fastaiv1 and neural nets trained in fastai (v2) would not deploy. Outdated functions for loading neural networks (pkl files) changed for new ones.
Additionally loosened library version requirements to not conflict with fastai (v2)
