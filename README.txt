The files in this repo are modifications of files provided by Dr. Ken Shen during 2015 MESA Summer School. 

The original files were obtained from the following site: https://doi.org/10.5281/zenodo.2603640

The files have been modified to make them compatible with mesa-r15140 version (latest as of April 2021), along with some minor changes to inlist files.

The file structure is pretty standard.

The run tested in mesa-r15140 is following:
Merger of 0.45 + 0.35 Msol helium WD remnant and it's evolution.

The original files were written for mesa-r7624 using mesasdk-x86_64-linux-20150908.tar.gz

For relaxing the model, the name of the inlist file to use is "inlist_relaxentropy_before"
After relaxation, the evolution is carried out using the inlist file "inlist_relaxentropy_after"

The analysis of the run can be carried out using the analysis scripts inside the analysis_scripts.tar file.

--------------------Sudarshan Neopane, April 2021 
