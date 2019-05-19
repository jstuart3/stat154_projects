# Stat 154, Project 2
## Classifying Cloud Cover Images

**Reproducibility**  
**Step 1**  

1. Inside the `rmd_files` directory you will find the summary portion of the report. That files can simply be open and run.
1. Inside the `rmd_files` directory you will also find the EDA portion of the report. To run this file, but sure to set the file path to the image data when reading in those csv's. Similarly with the cross validation portion of the report.

**Step 2**
1. Next, inside `from_nikhil` directory, you will find the three main R markdown files for the modelling portion of the report.
1. `split_k_fold.Rmd` must be run first as it writes csv files to be used in later parts of the analysis. Our cross validation function can also be found here.
1. Then, `first_split.Rmd` and `second_split.Rmd can be opened and run. To do so, make sure to set the file path to the data written out by `split_k_fold.Rmd`. Once you have done so, `first_split.Rmd` will perform the modelling on the first split of data created in `split_k_fold.Rmd` and `second_split.Rmd` will run the modelling on the second split.
1. Finally, our final report can be found in the `pdfs` directory. The file is named project02_final_report.pdf`.