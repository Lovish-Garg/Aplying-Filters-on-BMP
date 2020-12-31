# Aplying-Filters-on-BMP
In this repository I have uploaded my project in c which applies different filters on BMP files.

This program is not OS specific and this program will also work in Linux or any other OS.

<h4>1. To use this program you first need to create an .exe and then run file also providing command-line arguments.
<br><br>Syntax:</h4>

<p style="background-color: gray">./filter -filter pathofImage OutputImage</p>
<br>
<h4>You can also run the below mentioned commands on your local but for Windows instead of <p style ="background-color: rgb(10, 10, 10)">./filter use just filter</p></h4>
<h3>The Filters available are-><br>
1 . Greyscale<br>
2 . Sepia<br>
3 . Edge-Detection<br>
4 . Blur<br>
5.  Reflected<br>
</h3>
<br>
<h4>Some bmp files and their output files are also provided in thsi repository in Output and Images folder</h4>

<h3>Here are some examples:</h3>

<p>Command: ./filter -e images/yard.bmp Output/yard.bmp<br><h1>Original:<h1></p>
<img src = "images/yard.bmp" alt = "Pic of yard.bmp">
<h1>Edge-Detection</h1><img src = "Output/yard.bmp" alt = Output "Pic of Output yard.bmp">
 
<p>Command: ./filter -g images/stadium.bmp Output/stadium.bmp<br><h1>Original:<h1></p>
<img src = "images/stadium.bmp" alt = "Pic of Stadium.bmp">
<h1>Grayscale</h1><img src = "Output/stadium.bmp" alt = Output "Pic of Stadium.bmp">
<br>
<p>Command: ./filter -s images/courtyard.bmp Output/courtyard.bmp<br><h1>Original:<h1></p>
<img src = "images/courtyard.bmp" alt = "Pic of courtyard.bmp">
<h1>Sepia</h1><img src = "Output/courtyard2.bmp" alt = Output "Pic of Output courtyard.bmp">
  
<p>Command: ./filter -b images/tower.bmp Output/tower.bmp<br><h1>Original:<h1></p>
<img src = "images/tower.bmp" alt = "Pic of tower.bmp">
<h1>Blur</h1><img src = "Output/tower.bmp" alt = Output "Pic of Output tower.bmp">
 
<p>Command: ./filter -r images/courtyard.bmp Output/courtyard2.bmp<br><h1>Original:<h1></p>
<img src = "images/courtyard.bmp" alt = "Pic of courtyard.bmp">
<h1>Reflected</h1><img src = "Output/courtyard.bmp" alt = Output "Pic of Output courtyard.bmp">
  
