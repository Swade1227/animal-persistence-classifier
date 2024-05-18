OVERVIEW:

This project starts by obtaining persistence data from 3D mesh clouds of several animals, each with several poses. 
The persistence data is then used to train several machine learning classifiers (SVM and KNN) and then evaulated on accuracy.
The 3D pointclouds were obtained at https://people.csail.mit.edu/sumner/research/deftransfer/data.html#download 

The general outline is as follows:

1. Obtain 3D mesh data of animal models in different poses
2. Create reduced size point clouds with those meshes
3. Compute persistence diagrams from the point cloud data
4. Visualize persistence landscapes
5. Visualize persistence images
6. Use Multi Dimensional Scaling
7. Create persistence images to train on
8. Train multi-class SVM (one vs one) / evaluate
9. Train KNN / evaluate

SETUP:

The setup requirements are minmal. Just open the ipynb file and run the code. Each section of the project is further organized in the notebook.
   
