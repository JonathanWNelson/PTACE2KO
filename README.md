# PTACE2KO

This is the analysis of the PT ACE2 KO snRNAseq dataset.

Kidney nuclei from PT ACE2 KO and Control mice treated with Saline or AngII were isolated and purified by Fluorescence-activated nuclei sorting (FANS) and sequenced on the 10X Chromium Controller.

**GEO Files**

The Cell Ranger Outputs can be found at GSE253448

**Mouse Samples**

Sample Name / Mouse ID / Cre Status / Treatment

#1	2584	Cre -	Saline <br>
#2	2580	Cre +	AngII <br>
#3	2583	Cre +	Saline <br>
#4	2743	Cre -	AngII <br>
#5	2582	Cre +	Saline <br>
#6	2701	Cre -	AngII <br>
#7	2744	Cre -	Saline <br>
#8	2581	Cre +	AngII <br>

**File Index**

1) Preprocessing Pipeline <br>
   a) 2580_PT_ACE2_KO_AmbientRNA_Doublet_Removal.Rmd <br>
   b) 2581_PT_ACE2_KO_AmbientRNA_Doublet_Removal.Rmd <br>
   c) 2582_PT_ACE2_KO_AmbientRNA_Doublet_Removal.Rmd <br>
   d) 2583_PT_ACE2_KO_AmbientRNA_Doublet_Removal.Rmd <br>
   e) 2584_PT_ACE2_KO_AmbientRNA_Doublet_Removal.Rmd <br>
   f) 2701_PT_ACE2_KO_AmbientRNA_Doublet_Removal.Rmd <br>
   g) 2743_PT_ACE2_KO_AmbientRNA_Doublet_Removal.Rmd <br>
   h) 2744_PT_ACE2_KO_AmbientRNA_Doublet_Removal.Rmd <br>
3) Sample Integration and Cluster Identification <br>
   a) PT_ACE2_KO_all_Merging and Integration_AllSamples.Rmd <br>
   b) PT_ACE2_KO_AllSamples_clustering_jwn101823.Rmd <br>
5) Analysis of DEGS and Pathways <br>
   a) PT_ACE2_KO_AllSamples_clustering_jwn101723_DEGs.Rmd  <br>
   b) PT_ACE2_KO_Transporters_11202023_jwnPTpathwaysb_jme.Rmd  <br>
   c) PT_ACE2_KO_Pathways_GO.Rmd  <br>
7) Figures from Manuscript <br>
   a) Figure 7 and 8.Rmd <br>
   b) Supplemental Figures Final.Rmd <br>
