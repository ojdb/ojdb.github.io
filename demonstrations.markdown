---
layout: page
title:  "Demonstrations"
categories: #
---
This page contains links to some scietific demonstrations based on the [research papers][ojdb-papers]. 

[<img style="float: right;" 
src="./demonstrations/implicitcubic/implicitcubic.png" 
height="120">][ojdb-demo-cubic]
[**A basis for the implicit representation of planar rational cubic 
Bézier curves**][ojdb-demo-cubic]  
This demonstration implements the method described in the above paper on the GPU using WebGL and Three.js.  
It works by evaluating the implicit representation of a rational planar cubic Bézier curve for variable control points and weights, at every pixel in the window (using your GPU).  
The initial setup has control points at $$(-0.25, -0.25), (-1.0, 1.0), (-1.0, 1.0)$$ and $$(0.25,-0.25),$$ and control weights equal to one.  
The control points are selected using the number keys 1,2,3 or 4 (press 5 to deselect all control points), and are controlled by mouse movements.  
The weights are increased or decreased using the keys directly under the respective number on a standard QWERTY keyboard (e.g. for control point 1, the key 'q' increases the weight and 'a' decreases the weight).  
The arrow keys give freedom to move around and the 'z' and 'x' keys can be used to zoom in and out.  

You can find the source code for this demonstration at:  
{% include icon-github.html username="oliverjdb" %} /
[implicitcubic](https://github.com/oliverjdb/oliverjdb.github.io/blob/master/demonstrations/implicitcubic/index.html)


[ojdb-demo-cubic]:   ./demonstrations/implicitcubic/index.html
[ojdb-papers]:       ./academic-papers.html
