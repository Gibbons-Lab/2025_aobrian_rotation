# Statins and Diet
Statins are widely used medications that lower low-density lipoprotein (LDL) cholesterol levels, significantly reducing the risk of cardiovascular disease. Research in the Gibbons Lab has shown that variations in the gut microbiome influence statin efficacy, potentially explaining why some patients respond better to treatment than others. Additionally, dietary factors, such as grapefruit or other CYP enzyme inhibitors, are known to alter statin metabolism, further highlighting the interplay between diet, microbiota, and drug response.

Using a novel tool for metagenomic estimation of dietary intake (MEDI) developed in the Gibbons Lab, we will explore the interactions between specific foods, gut microbes, and statin efficacy in patients with varying levels of cardiometabolic health (MetaCardis cohort) By integrating metagenomic data with biomarkers like HMG-CoA levels in the blood (a key precursor in cholesterol synthesis) and HbA1c (statins are known to increase insulin resistance, as an undesirable side-effect), we aim to identify dietary and microbial factors that enhance or impair statin performance. This approach could lead to personalized dietary recommendations that optimize statin therapy, improving patient outcomes and advancing precision medicine in cardiovascular care.

## In this Repo you will find:
**Data folder:** 
has the combined food abundance output csv from running medi on metacardis projects(PRJEB37249 & PRJEB38742)
some of the processed csv files from the metacardis paper published on cardiometabolic disease

**Notebooks:**
the regression notebook has most of my work but its a little messy. It has everything from data processing to regressions to making plots. Theres also a plots noteboook and a CoVars notebook that are short and require certain csvs from the first notebook. The last notebook is where I calculate beta diversity of the diet ploted PCoA colored by different features and also beta diversity of the microbes and the metabolome. 

**Rotation Presentation**
In case it's easier to look at the presentation than the jupyter notebooks

