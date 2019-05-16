# Find Necessary R Packages in a Project Folder
If you want to reverse engineer which R packages (from the already installed ones) do you really need to load in in your project then this tiny script may help you. Just add the root of your R project folder as an argument,
and it will pick recursively out all the used R functions and their probable package counterparts from the .R files
from the project folder and its subfolders.
The results will be displayed only on standard out.

usage:        findAllNecRFunInProj <full/URL/to/R_project_folder>

for instance: findAllNecRFunInProj '~/Projects/SampleProject/'

Runs only on linux and requires installed R environment and data.table, NCmisc & knitr packages.
