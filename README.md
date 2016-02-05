# my_anaconda_activate


inspired by https://github.com/sotte/conda_auto_activate.
(changed the function call to an export)

Automatically activate a conda environment when entering folders/project.

conda_auto_activate automatically activates a conda environment when enterring a folder that contains a .condaauto file. The first line in the .condaauto file is the name of the conda environment.

To make this work you have to source conda_auto_activate.sh from your ~/.bashrc.

source ~/path_to/conda_auto_activate.sh


