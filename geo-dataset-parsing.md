Systems Biology Analysis of 3T3-L1 Differentiation
========================================================

This was based on the tools learned about in the Coursera course.  This code was most recently run on Sun Oct 27 15:18:56 2013 and is stored at /Users/davebridges/Documents/Research/differentiation.

Dataset Acquisition
--------------------


```
## Parsing....
```


The data was obtained from GEO using the dataset in GEO accession GSE6794, which is described in (<a href="http://dx.doi.org/10.1016/j.cmet.2007.01.005">Cheung et al. 2007</a>).  This file is described as:

**3T3-L1 fibroblasts are a commonly used in vitro model for adipogenesis.  When induced with hormones, they differentiate into mature fat cells.  Here, microarrays were used to study 3T3-L1 adipose differentiation through time.**

The file was downloaded, annotated and reformatted into an input file for GATE.  This file was saved as **Differentiation Time Course.clu**.

References
-----------


- Kevin J. Cheung, Iphigenia Tzameli, Pavlos Pissios, Ilsa Rovira, Oksana Gavrilova, Toshio Ohtsubo, Zhu Chen, Toren Finkel, Jeffrey S. Flier, Jeffrey M. Friedman,   (2007) Xanthine Oxidoreductase is A Regulator of Adipogenesis And Pparγ Activity.  *Cell Metabolism*  **5**  115-128  [10.1016/j.cmet.2007.01.005](http://dx.doi.org/10.1016/j.cmet.2007.01.005)


Session Information
---------------------



```
## R version 3.0.2 (2013-09-25)
## Platform: x86_64-apple-darwin10.8.0 (64-bit)
## 
## locale:
## [1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8
## 
## attached base packages:
## [1] parallel  stats     graphics  grDevices utils     datasets  methods  
## [8] base     
## 
## other attached packages:
## [1] biomaRt_2.18.0      knitcitations_0.5-0 bibtex_0.3-6       
## [4] GEOquery_2.28.0     Biobase_2.22.0      BiocGenerics_0.8.0 
## [7] knitr_1.5          
## 
## loaded via a namespace (and not attached):
## [1] digest_0.6.3   evaluate_0.5.1 formatR_0.9    httr_0.2      
## [5] RCurl_1.95-4.1 stringr_0.6.2  tools_3.0.2    XML_3.95-0.2  
## [9] xtable_1.7-1
```

