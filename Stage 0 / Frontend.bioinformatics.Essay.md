R shiny
---

Author (@slack):

Manar Tarek (@ManarTj)

# Introduction

Shiny is web framework for R language. It enables R users to make web
applications directly by using R. cancer researchers can use it to create genomic data visualisation and analysis without need to strong web development skills.

# R shiny in cancer research

Several tools are developed by this package to help researchers to
analyse and visualise genomic data in addition to identification and
prediction of drug targets and drug responses respectively.
 
 TPWshiny:

It is app developed by R Shiny package to facilitate examination of drug
responses ( anti-cancer drugs) of cell lines.

It provided by drug concentration, gene information and tissue type,
then it present analysis of the drug response inform of scatter plots,
venn diagrams, time series and heat maps.( Peter *et al* , 2022)

GNOSIS:

It is tool developed by R Shiny package enables researchers to upload
and explore their data, then it provides data visualisation and survival
statistical analysis aid in prognosis and mutation analysis. (King *et
al*, 2022)

ShinyDeepDR:

It is tool developed by r shiny package, enables prediction of
anti-cancer drugs which is most suitable for their cell line or tumor
sample within 265 anticancer drugs at GDSC. It have 2 options, find drug
which predict the most suitable drug and find sample which search for
other samples have same features in TCGA CCLE databases and find their
real or predicted drug. ( wang *et al*, 2024)

![](media/image1.png){width="1.4755555555555555in"
height="1.011111111111111in"}

( wang *et al*, 2024)

# Case study

Holomics, researchers developed by using R shiny package to analyse diffrent omics Datasets. 
Data upload: user should upload Datasets including transcriptomics, genomics, proteomics and macrobiotics. Holomics undergoes initial filtrating and remove all irrelevant data. 
Single omics analysis: each Dataset is analysed statistically to catch the most relevant points and information in it and to reduce complexity.  
Multi-omics integration: Holomics undergoes correlation analysis between diffrent layers of the Datasets to provide visualised analysis with informative insights.  

They used it to analyse integrated omics of sugar beets storability and it results insights about key factors about improving sugar beets
storability. ( Munk *et al*, 2024)

# Conclusion

R shiny package have important role in cancer research as it is flexible, enables researchers to customize their own tool according to their needs and facilitate collaboration of the team as it enables diffrent users to access to the same data analysis tools.
It can also integrated with machine learning to be used in Personalized Medicine  according to patient's genetic profile and in prognosis by developing risk prediction models detect progression and recurrence of the disease.

# References

1.[[https://rbasics.org/packages/shiny-package-in-r/]{.underline}](https://rbasics.org/packages/shiny-package-in-r/).

2\. Li-Ju Wang, Michael Ning, Tapsya Nayak, Michael J. Kasper,
Satdarshan P. Monga, Yufei Huang, Yidong Chen, Yu-Chiao
Chiu,shinyDeepDR: A user-friendly R Shiny app for predicting anti-cancer
drug response using deep learning.Patterns,Volume 5, Issue
2,2024,100894,ISSN 2666-3899.

[[https://doi.org/10.1016/j.patter.2023.100894]{.underline}](https://doi.org/10.1016/j.patter.2023.100894).

3.Zhang P, Palmisano A, Kumar R, Li MC, Doroshow JH, Zhao Y. TPWshiny:
an interactive R/Shiny app to explore cell line transcriptional
responses to anti-cancer drugs. Bioinformatics. 2022 Jan
3;38(2):570-572.

[[https://doi.org/10.1093/bioinformatics/btab619]{.underline}](https://doi.org/10.1093/bioinformatics/btab619).

4.King L, Flaus A, Coughlan S et al. GNOSIS: an R Shiny app supporting
cancer genomics survival analysis with cBioPortal,HRB Open Res 2022, 5:8
[[https://doi.org/10.12688/hrbopenres.13476.2]{.underline}](https://doi.org/10.12688/hrbopenres.13476.2).

5\. Munk, K., Ilina, D., Ziemba, L. et al. Holomics - a user-friendly R
shiny application for multi-omics data integration and analysis. BMC
Bioinformatics 25, 93 (2024).
[[https://doi.org/10.1186/s12859-024-05719-4]{.underline}](https://doi.org/10.1186/s12859-024-05719-4).
