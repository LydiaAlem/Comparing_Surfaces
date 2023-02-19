# Comparing 3D Surfaces

## This was a project I completed in my Multivariable Calculus (MATH 2263) Course!

This research project was undertaken to conduct a thorough comparative analysis of two distinct 3D shapes, namely the paraboloid and the cone. 
The primary aim of this study was to examine the similarities and differences between the two shapes and to understand their unique characteristics. 
The project involved utilizing the powerful LaTeX typesetting system, specifically the Overleaf platform, to create highly detailed and 
accurate contour maps that could be analyzed in detail. The initial step involved the creation of a comprehensive contour map, which
was spanned by the -xy plane. This contour map allowed for a clear understanding of the characteristics of the tangent line at the
point (0,0,0), which was essential for the subsequent stages of the analysis.

## Getting Started 

When creating the 3D graphs, these were the following packages that were utilized: 
```tex
\usepackage{pgfplots}
\pgfplotsset{compat=1.16}
\usepackage{graphicx}
\usepackage{pgfplots}
\pgfplotsset{compat=1.17}
\usepackage{amsmath}
```


### Dependencies

* Overleaf provides an amazing feature which allows for writing and compiling code simultaneously [Click here for information](https://www.latex-project.org/get/)

### Installing

* LaTeX installation is needed if you want to create your own graphs. [Click here for information](https://www.overleaf.com/learn/latex/Choosing_a_LaTeX_Compiler)

### Executing program
* Begin by including the tikz package in your LaTeX file
```tex
\usepackage{tikz}
```

* Inside of the document{...} body, include the following:
```tex
\begin{tikzpicture}
...
\end{tikzpicture}
 ```
 
* Once inside of the tizkpicture, begin by creating the drawing command:
```tex
%example #1: drawing a line from one point to another : 
\draw (0,0) -- (1,1);

%example #2: filling in a shape:
\filldraw[fill=red] (0,0) -- (1,0) -- (1,1) -- cycle;
```
[More examples from the tizk package can be found here](https://www.overleaf.com/learn/latex/TikZ_package)


## Images generated from the package: 
<img width="924" alt="Screenshot 2023-02-18 at 8 38 50 PM" src="https://user-images.githubusercontent.com/107647071/219909167-4e606ce1-0ea3-47c4-a360-1bdfc60055d2.png">

<img width="376" alt="Screenshot 2023-02-18 at 8 12 38 PM" src="https://user-images.githubusercontent.com/107647071/219909168-e7e126d8-972d-4e5d-95b2-c9cb4ad1b9d7.png">


## Version History
* Compiled with libpng 1.6.37; using libpng 1.6.37
* Compiled with zlib 1.2.11; using zlib 1.2.11
* Compiled with xpdf version 4.03
