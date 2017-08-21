# Masters_Project
A project to visualize astronomical data such as star clusters, galaxies and dark matter maps using 3D data cubes, AMR files and VDBs. A pipeline tool has been developed to analyze and plot data points collected from various astronomical agencies. 

Files:

1. AstroVis.hdanc : The digital asset built using Houdini 16
2. AstroVis.hipnc : A sample HIP file to use to test the digital asset.
3. amr_shader.hdanc : A sample shader used to shade VDB volumes built using AMR file. (http://www.ytini.com/)
  
Instructions for shader :
1. Install the shader asset
2. Use a file Sop to import the built VDB volume
3. Set the VDB Path parameter on the shader to the path of the VDB file
4. Set Max Data Value to 7. 
5. Set Color Field under the Color tab to 'density'
6. Change the color ramp as required.
