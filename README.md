# Comparing 3D Surfaces

This research project was undertaken to conduct a thorough comparative analysis of two distinct 3D shapes, namely the paraboloid and the cone. 
The primary aim of this study was to examine the similarities and differences between the two shapes and to understand their unique characteristics. 
The project involved utilizing the powerful LaTeX typesetting system, specifically the Overleaf platform, to create highly detailed and 
accurate contour maps that could be analyzed in detail. The initial step involved the creation of a comprehensive contour map, which
was spanned by the -xy plane. This contour map allowed for a clear understanding of the characteristics of the tangent line at the
point (0,0,0), which was essential for the subsequent stages of the analysis.



## Languages & Software used:

<img src="https://github.com/LydiaAlem/Applying-Stokes-Theorem/assets/107647071/a55dcd53-66b1-4437-b64b-2fc759a02624" alt="overleaf Logo" width="155" height="50">
<img src="https://github.com/LydiaAlem/Applying-Stokes-Theorem/assets/107647071/7586c7d7-2255-4bb6-9b6e-4cb0573b4c23" alt="LaTeX Logo" width="80" height="80">

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


## Getting Started

1. Go to Overleaf and log in to your account.
2. Create a new blank project or open an existing project where you want to pull the Applying Stokes repository.
3. In your Overleaf project, navigate to the left sidebar and click on the "Git" button.
4. In the Git menu, click on the "Pull from GitHub" option.
5. Copy the following command to clone the repository:
   
`git clone https://github.com/LydiaAlem/Applying-Stokes-Theorem.git`

6. Open your preferred terminal or command prompt and navigate to the desired directory where you want to save the clone.
7. Paste the copied command into the terminal and press Enter to execute it. This will clone the Applying Stokes repository to your local machine.
8. Once the cloning process is complete, go back to Overleaf and click on "Upload Project" in the left sidebar.
9. Choose the option to upload a ZIP file.
10. Locate the cloned folder on your local machine and compress it into a ZIP file.
11. Upload the ZIP file to Overleaf.
12. Overleaf will extract the contents of the ZIP file and create a project with the Applying Stokes repository.

## Dependencies

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

<img width="306" alt="Screenshot 2023-02-18 at 8 47 31 PM" src="https://user-images.githubusercontent.com/107647071/219909429-620b0001-d544-4ef4-9c97-79d66071e367.png">

<img width="303" alt="Screenshot 2023-02-18 at 8 46 32 PM" src="https://user-images.githubusercontent.com/107647071/219909432-8667dad9-09c7-459b-81e8-d8452a7643c3.png">

<img width="299" alt="Screenshot 2023-02-18 at 8 44 50 PM" src="https://user-images.githubusercontent.com/107647071/219909582-8aa046b9-1f76-4390-856e-a2b3c4592804.png">


## Version History
* Compiled with libpng 1.6.37; using libpng 1.6.37
* Compiled with zlib 1.2.11; using zlib 1.2.11
* Compiled with xpdf version 4.03
