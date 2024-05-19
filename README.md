OVERVIEW:

This project starts by obtaining 3D mesh clouds of several animals, each with several poses. 
Then we extract persistence features from those pointclouds and use it to train several machine learning classifiers (SVM and KNN) and evaulated them on accuracy.
The 3D pointclouds were obtained at https://people.csail.mit.edu/sumner/research/deftransfer/data.html#download 

The general outline is as follows:

Section 1. Obtain 3D mesh data of animal models in different poses
Section 2. Create reduced size point clouds with those meshes
Section 3. Compute persistence diagrams from the point cloud data
Section 4. Visualize persistence landscapes
Section 5. Visualize persistence images
Section 6. Use Multi Dimensional Scaling to scale down and visualize the point cloud data
Section 7. Train models on scaled pointcloud data and assess accuracy for comparison
Section 8. Obtain persistence images of pointclouds
Section 9. Train multi-class SVM (one vs one) / on images
Section 10. Train KNN / on images
Section 11. Compare and evaluate

Each section can be individually acccesses/jumped too by using the table of contents feature in the top left menue of the notebook

SETUP:

The setup requirements are minmal. Just download and open the ipynb file, then run the code. Each section of the project is further organized in the notebook.
   
