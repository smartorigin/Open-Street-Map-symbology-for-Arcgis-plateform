# Open-Street-Map-symbology-for-Arcgis-plateform
A repo that holds various icons to symbologize an ArcGIS service

![assets/header.jpg](assets/header.jpg "header")

In this repo you will find some icons to illustrate an ArcGIS service that holds open street map data.

These icons are located in the `symbology` folder and are ready to use with the ArcGIS platform (no post process needed, just publish with a size of `24pt`).

If you wan't to edit the icons you can use the provided Adobe Illustrator file `osm.ai` located in `source` folder. The file is structured as follow : 
* one `layer` for each `outline`
* one `layer` for each `icon`

Tricks to make a good export from this `.ai` file : 

  1. Keep the icon squared (width=height)
  2. Export in 72 dpi from Adobe Illustrator
  3. Convert to 96 dpi in Adobe Photoshop
  4. When publishing set value to : `(width in px)*0.75`pt
  
Further reading on the subject :
* https://forums.adobe.com/thread/321621
* http://blogs.esri.com/esri/arcgis/2014/04/17/arcgis-solutions-symbols-now-have-a-repo-on-github/
  
Sample usage : https://services.arcgis.com/KuaABtfkgFHV6L3h/arcgis/rest/services/Cannes__OSM/FeatureServer/
