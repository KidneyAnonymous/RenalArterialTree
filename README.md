# Kidney Vascular Tree

Here we present more results from our paper in this GitHub page.

The source code for the paper is available to the reviewers upon request and will be made publicly available upon acceptance with the GitHub repo under an open-source license. 

Raw data and image processing algorithms can be exchanged through a collaboration agreement. 
Processed data and analysis algorithms can be made available upon request.

##  1. Gif results in 3D
Here we show some animations of our generated renal arterial tree in ParaView. 
Different gifs represent the tubes are colored by different properties, e.g., radius, flow, pressure.
These gifs are stoed in ```visualizations``` folder.

### Colored by radius
 ![](visualizations/radius1.gif) 
### Colored by flow
 ![](visualizations/flow.gif) 
### Colored by pressure
 ![](visualizations/pressure.gif) 

## The flow and pressure coloring is quite sensitive to outliers. Therefore, we also rescale them by manually setting a smaller range 
### Colored by rescaled flow
 ![](visualizations/flow_rescaled.gif) 
### Colored by rescaled pressure
 ![](visualizations/pressure_rescaled.gif) 


[//]: # (<img src="visualizations/pressure.gif" width=30% height=50%>)

[//]: # (<img src="visualizations/pressure.gif" width=30% height=50%>)

[//]: # (<p float="center">)

[//]: # (  <img src="visualizations/radius.gif" width="40%" />)

[//]: # (  <img src="visualizations/radius.gif" width="40%" /> )

[//]: # (</p>)


You can visualize vessel thickness in ParaView by applying a Tube filter, and selecting node radius as Vary Radius.
Then finally choose coloring based on different features

![](plots/paraview_tube.png)

## 4. Artificial kidney dataset
The 3D artery segmentation labalmap derived from the generated arterial tree is in ```fake_artery_label.nii.gz```  
stored in the folder ```VesselDataset```.  The corresponding image is shown below in the right image.
The 3D nifty image is too large to be included in GitHub.
<p float="center">
  <img src="plots/fake_label.png" width="45%" />
  <img src="plots/fake_scan.png" width="45%" /> 
</p>


## 5. Original micro-CT scan

The original scan and the semi-automatic artery segmentation label map cannot be made public for now, 
but can be shared upon request. 

