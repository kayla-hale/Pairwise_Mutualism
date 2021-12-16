# Pairwise_Mutualism
This code base creates the raw image files used in the Hale et al. 2021 manuscript entitled "Simple mechanisms of plant reproductive benefits yield different dynamics in pollination and seed dispersal mutualisms" for The American Naturalist (Manuscript 60685R2). Files are Mathematica Notebooks that find numerical solutions to the pairwise mutualism models in the main text.

Citation:
Simple mechanisms of plant reproductive benefits yield different dynamics in pollination and seed dispersal mutualisms
Kayla R. S. Hale, Daniel P. Maes, Fernanda S. Valdovinos
doi: https://doi.org/10.1101/2021.05.05.442848

All files are Mathematica Notebooks that find numerical solutions to the pairwise mutualism models in the main text. 
The "Pollination_zenodo.nb," "Negative Density-Dependence_zenodo.nb," and "Germination_zenodo.nb" files create the phase plane diagrams presented in Figs. 1, 2, and 3. 
NOTE: (The uncommented (raw) notebooks are also available too but redundant. The "_zenodo" copies are those that will be logged on Zenodo.)

Within each file, each code chunk includes the parameter values and commands for finding nullclines, equilibria, and separatrices shown in each panel of Figs. 1-3. 
The "Bifurcation.nb" file includes code chunks that draws bifurcation diagrams for plants and animals for each of the models, using an illustrative set of parameters (presented in Fig. 4). 
In all cases, equilibria were manually colored as stable or unstable by inspecting the local dynamics as computing this numerically was too slow. 
Threshold and Allee regions were shaded manually in Illustrator.
To run these models dynamically, select "Evaluate Notebook" or "Evaluate Cells" one at a time from the "Evaluation" drop down menu.
To most easily explore the dynamics of these models, run them with only the StreamPlot (vector field) and ContourPlots (non-trivial nullclines) showing, commenting everything else out (especially the separatrices) to avoid computational issues while manipulating parameters. 
For a publication-quality image, turn the other commands back on and specify the numerical limits or coloring according to the specific parameter case. 
