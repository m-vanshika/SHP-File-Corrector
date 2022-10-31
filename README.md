# SHP-File-Corrector
It is a QGIS plugin which can be used to edit an SHP file to adjust the borders of the lines and reduce the errors caused by automatically generated wrong boundaries and correct them with manual correction.

Demonstration of Plugin:




https://user-images.githubusercontent.com/61660633/195330878-a2be51c9-cbb5-405f-b8f3-7f098d00dec6.mp4

Steps to use the plugin:

1.Install and start the plugin in QGIS
2. Select the SHP layer that needs to be edited and give the path for final output layer
3. From the drop-down which contains all the features of the above selected shp layer, add main features to the temporary new layer and remove the rest
4. Choose Line , point or polygon , after which the drop-down will contain list of respective features, which can be edited using qgis edit options, and saved to final layer.
5. Once all the required features are added to final layer , save the final shp, this will save all the line point and polygon geometry in the path stated in first step
