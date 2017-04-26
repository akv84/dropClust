# dropClust

## Prerequisites:
1. Python  (>=2.7), R
2. Python sklearn package
3. R dependencies will be installed automatically when executing the main script.
4. C compiler for Windows users.

Clone/Download the "dropClust" repository.

## Executing the script (Linux):

1. Download pbmc 68K dataset from:
http://s3-us-west-2.amazonaws.com/10x.files/samples/cell/pbmc68k_rds/pbmc68k_data.rds
and put the pbmc68k_data.rds file in the "data" directory. The annotation file has already been placed there.

2. Execute dropClust_main.R
Update the working directory and data directory paths in the script.

3. Obtain the cell-type specific genes and the heatmap by executing the DE_plot.R script.


## Executing the script (Windows):

Build windows executable from "louvain/src" files inside the "louvain" directory beforre executing the R scripts.
