---
layout: page
title:  "Demonstrations"
categories: #
---
This page contains links to some scientific demonstrations based on my [research papers][ojdb-papers]. 

## A basis for the implicit representation of planar rational cubic Bézier curves

[<center><img src="./demonstrations/implicitcubic/implicitcubic.png" align="middle" height="320"></center>][ojdb-demo-cubic]

# Method:

This demonstration implements the method described in the above paper on the GPU using WebGL and Three.js.
It works by evaluating the implicit representation of a rational planar cubic Bézier curve for variable control points and weights, at every pixel in the window (using your GPU).  


# User interaction:  

* The control points can be selected using the number keys 1,2,3 or 4 (press 5 to deselect all control points), and are controlled by mouse movements.  
* The weights are increased or decreased using the keys directly under the respective number on a standard QWERTY keyboard (e.g. for control point 1, the key 'q' increases the weight and 'a' decreases the weight).  
* The arrow keys give freedom to move around and the 'z' and 'x' keys can be used to zoom in and out.  

# Source code:  

You can find the source code for this demonstration at: {% include icon-github.html username="oliverjdb" %} /
[implicitcubic](https://github.com/oliverjdb/oliverjdb.github.io/blob/master/demonstrations/implicitcubic/index.html)


[ojdb-demo-cubic]:   ./demonstrations/implicitcubic/index.html
[ojdb-papers]:       ./academic-papers.html
