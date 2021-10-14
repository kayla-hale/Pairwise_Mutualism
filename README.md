# Pairwise_Mutualism
This code base creates the raw image files used in the Hale et al. 2021 manuscript entitled "Dynamics of pollination and seed dispersal mutualisms at low density" for The American Naturalist (Manuscript 60685R1). 
All files are Mathematica Notebooks that find numerical solutions to the pairwise mutualism models in the main text. 
The "Pollination.nb," "Negative Density-Dependence.nb," and "Germination.nb" files create the phase plane diagrams presented in Figs. 1, 2, and 3. 
Within each file, ach code chunk includes the parameter values and commands for finding nullclines, equilibria, and separatrices shown in each panel of Figs. 1-3. 
The "Bifurcation.nb" file includes a code chunk that draws bifurcation diagrams for plants and animals for each of the models, using an illustrative set of parameters. 
In all cases, equilibria were manually colored as stable or unstable by inspecting the local dynamics as computing this numerically was too slow. 
Threshold and Allee regions were shaded manually in Illustrator.
To run these models dynamically, select "Evaluate Notebook" or "Evaluate Cells" one at a time from the "Evaluation" drop down menu.
To most easily explore the dynamics of these models, run them with only the StreamPlot (vector field) and ContourPlots (non-trivial nullclines) showing, commenting everything else out (especially the separatrices) to avoid computational issues while manipulating parameters. 
For a publication-level image, turn the other commands back on and specify the numerical limits or coloring according to the specific parameter case. 
