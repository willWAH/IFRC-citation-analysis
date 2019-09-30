# IFRC-citation-analysis
In 2017, the International Federation of Red Cross and Red Crescent Societies (IFRC) carried out a citation analysis of a sample of its document base. The analysis followed evidence from production to use in order to assess what kind of evidence is produced and the degree to which it is taken up by other materials.
The R script provided here was used to analyse the degree distribution of our graphs. The RStudio IDE is free to download at: https://rstudio.com/products/rstudio/download/. The script obtains the degree distribution from a Pajek graph, which we created in SocNetV. The script is ready to use as is, with only one change needing to be made at line 12 (see below). The first 10 lines install and load the required packages. The next few lines load the Pajek file generated in Gephi. The only change to be made is at line 12, where the directory path in the file_path variable must point to your Pajek file. Make sure all backslashes are replaced with forward slashes '/'.
A full explanation of the script is provided in Hankey and Pictet (2019) Guidelines for carrying out a citation analysis: following evidence from production to use, Knowledge Management for Development Journal, forthcoming.
