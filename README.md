# WASH_CNMA
This repository includes all the data and the files needed to replicate all the results of the paper "Effectiveness of sandalone and multi-component water, sanitation and hygiene interventions to reduce mortality in childhood: a network meta-analysis"

This document contains all the instructions needed to replicate the results of the paper Effectiveness of stand-alone and multicomponent water, sanitation and hygiene interventions to reduce mortality in childhood: a network meta-analysis.

What is in the Zip folder?
The Zip folder “replication” contains all the files required to replicate the results (tables and chart) presented in the paper. In particular, the folder contains:
Four datasets for the analysis in Stata format:
•	netwashforR_paper.dta, which is used for the network meta-analysis
•	netwashforR_dis_paper.dta, which is used for the network meta-analysis including different categories 
•	netwashforRH_w_paper.dta, which estimates the network meta-analysis separately for improved and unimproved water initial conditions
•	netwashforRH_s_paper,dta, which estimates the network meta-analysis separately for improved and unimproved sanitation initial conditions
Two markdown files to replicate the results:
•	wash_paper_results.Rmd, which replicates most results included in the paper
•	interactions.Rmd, which replicates the results of the additive model and of the selection of the partial interaction model
Two excel documents used to build the tables included in the paper:
•	res_nma_w.csv which is used to replicate Table 1 of the paper
•	netsplit.csv, which is used to replicate Table 3 of the paper
Two additional files used to include references:
•	library.bib
•	apa.csl

System requirements
The analysis requires the R package. At the time of creating the replication folder we used the R version 4.4.3. 
The R code requires the following R packages: haven, dplyr, meta, netmeta, kableExtra, data.table, insight. The packages will be automatically installed when running the markdown file.


Instruction to run the files and replicate the results
The markdown files will replicate all the results (charts and tables) included in the paper. Both markdown files need less than 1 minute each to produce all the results.
Step 1
Create a folder in your C drive named “replication” and download the contents of the Zip file in this folder
Step 2
Open the R software, and from the R software open the markdown document wash_paper_results.Rmd.
Step 3
In the markdown file, click on the Knit button to create an HTLM file with all the output (output will be saved in wash_paper_results.html). You can also run the markdown file or the individual components of the file clicking the Run button.
Step 4 
Repeat Step 2 and Step 3 with the interaction.Rmd file, if you wish to see the results of the model selection process for the results in Table 1 of the paper (results will be saved in the file interactions.html)
