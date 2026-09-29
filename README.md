# Vivanco Lab – Legume–Wheat Cover Crop Microbiome Project

Overview

This repository contains the R code and supporting data used to analyze plant responses, root exudate metabolites, and rhizosphere microbial communities in the legume–wheat cover crop study. The code is provided to reproduce the statistical analyses, tables, and figures presented in the manuscript.

Antisar Afkairin1†, Mary Dixon1†, Jane Godfrey1 , Emma C. Byerly1, Alison Hamm2, Cassidy Buchanan3, Nathalie Munoz4, Daniel Manter2, and Jorge Vivanco1* 

File descriptions

1.	"Biomass-Code.Rmd" includes code to analyze differences in plant dry biomass among experimental groups.
o	Data inputs:
	"LegacyDryWeights.csv": Contains plant dry biomass measurements.
o	Data outputs:
	Statistical results and visualizations for shoot and root biomass.
	Shoot biomass: Figure 2 and Table S1.
Root biomass: Figure 3 and Table S2.

2.	"dbRDA.Rmd" includes code to perform distance-based redundancy analysis (dbRDA) to evaluate relationships between microbial community composition and explanatory variables.
o	Data inputs:
Microbial community data.
Associated sample metadata and explanatory variables.
o	Data outputs:
	dbRDA statistical results and ordination visualizations.
	Figure 4.
   Table S3.

3.	"P uptake & N uptake.Rmd" includes code to calculate and analyze plant phosphorus (P) and nitrogen (N) uptake.
o	Data inputs:
	Plant biomass and nutrient concentration data used to calculate P and N uptake.
o	Data outputs:
	Statistical results and visualizations for plant P and N uptake.
	Figure 5.
	Tables S4 and S5. 

4.	"Diff_Abund.Rmd" includes code to perform differential abundance analysis and identify bacterial taxa that differ among experimental groups.
o	Data inputs:
	Microbial abundance/count data.
	Sample metadata defining experimental groups.
o	Data outputs:
	Differential abundance statistical results.
	Identification and visualization of bacterial taxa that differ among experimental groups.
	Figure 6.
	Tables S6A–C.

5.	"functions.Rmd" includes code to identify and visualize predicted microbial functional genes associated with selected bacterial species using PICRUSt2/KEGG functional data.
o	Data inputs:
	PICRUSt2/KEGG predicted functional data.
	Microbial community data used to identify bacterial species of interest.
o	Data outputs:
	Predicted genes organized into microbial functional categories.
	Species–function–gene visualizations for functions associated with nutrient cycling, phosphate solubilization, siderophore production, biocontrol, and stress response.
	Figure 7.
	Table S7.

6.	"LEGUME_EXUDATE_GC-MS-ANALYSIS-ENRICHMENT.Rmd" includes code to analyze GC–MS root exudate metabolite data and evaluate differences in metabolite profiles among experimental groups.
o	Data inputs:
	"Ex_data2.csv": Contains root exudate metabolite data.
o	Data outputs:
	Statistical results for metabolite comparisons.
	Metabolite enrichment and abundance visualizations.
	Figures 8 and 9.
	Supplementary Figure S1.
	Table S8.






