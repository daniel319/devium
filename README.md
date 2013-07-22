DEVIUM
======

<b>D</b>ynamic multivariat<b>E</b> data analysis And <b>VI</b>s<b>U</b>alization Platfor<b>M</b>

A GUI for interactive plotting and analysis of multivariate data.

Demos
======
Prototypes for some of the analyses implemented in ```Devium``` can be viewed in the browser using the ```Shiny``` frame work. Check out some of the examples below.
- [Heirarchical Cluster Analysis](http://spark.rstudio.com/dgrapov/Heatmap/)
- [Basic Plotting] (http://spark.rstudio.com/dgrapov/Plotting/)
- [Principal Components Analysis Diagnostics] (http://spark.rstudio.com/dgrapov/PCA/)

 
 Including: 
 
  - GUI using RGtk2 toolkit implemented with gWidgests 
 
  - Dynamic plotting - base and ggplot2 
 
  - Linked brushing of multiple plots -  iplots
 
  - Network Visualizations - igraph (static, interactive and 3D), Cytoscape (RCytoscape)
 
  - Analyses - univariate and multivariate
 
  - Automated report generation - rsweave
  
  - Data import and linking with MS Excel and Google Spreadsheets
  
  - Successor to <a href="https://sourceforge.net/projects/imdev/">imDEV</a>, including improved interface and capabilities

Installation
======
<p>Eventually devium will be installed from R as a package and from alternative repositories where it can be bundled with GTK+ components.
For now it can be installed by using the source code in the devium/R directory.
Copy and paste the following code in to R to source the necessary files.</p>

 ```r
 #load package from github repo
source("http://pastebin.com/raw.php?i=JVyTrYRD")

#check out some of the functions (accesory objects will be cleaned up)
objects()

#launch GUI (watch R console for messages regarding the downloading of dependancies)
devium.gui()

 ```
 Note if you don't yet have the GTK+ toolkit installed you need to specify to "Install GTK+" when prompted from the R command line.
 
 Notes
 ======
 What started as an attempt to write GUIs using gwidgets has turned into an effort using Shiny.
