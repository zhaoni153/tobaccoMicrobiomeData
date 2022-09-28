# 16s rRNA sequencing data from mock communities and real tobacco samples

---
Ni Zhao (nzhao10@jhu.edu), Mo Li (mli171@jhu.edu), Glen Satten (GSatten@emory.edu)
---
## Overview
The github page contains the 16s rRNA sequencing data that are used in our paper <br/>
What Can We Learn about the Bias of Microbiome Studies from Analyzing Data from Mock Communities? Li, M., Tyx, R.E., Rivera, A.J., Zhao, N., Satten, G.A., *Genes*, In press  <br/>

## Details

This study used data from 4 different types of samples: the Zymo standard comprising cells (ZMC); the Zymo cell standard mixed with a biological matrix (ZMC + Matrix); samples of Swedish Snus, a smokeless tobacco product from Sweden that has been pasteurized; and samples comprising commercially available smokeless tobacco products. Each sample was processed by four extraction protocols: Protocol 1 (Base) serves as a baseline method, Protocols 2 (Enzymes), 3 (Lifeguard®) and 4 (RNAProtect®) can be considered as modifications of the Base method, which all aim at improving the DNA extraction efficacy by facilitating the bacterial lysis or by providing extra RNA protection. For the ZMC, ZMC + Matrix and Swedish Snus data we performed four replicate extractions for each protocol; thus, these sample sets each have 16 observations. 

The ZMC samples are constructed with a known (theoretical) composition. The theoretical compositions provided by Zymo Research based on kit batch number is: Staphylococcus—13.3%, Bacillus—15.7%, Lactobacillus—18.8%, Listeria—15.9%, Enterococcus—10.4%, Salmonella—11.3%, Escherichia Shigella—10.0%, Pseudomonas—4.6%.  The ZMC + Matrix samples were created by mixing the Zymo mock communities with the biological matrix from snus tobacco product. Here, the snus samples were prior pasteurized and thus can be considered free of bacteria. 


Each sample was analyzed using all four protocols; in addition, we conducted replicate extractions of each sample. For the ZMC, ZMC + Matrix and Swedish Snus data we performed four replicate extractions for each protocol; thus, these sample sets each have 16 observations. The smokeless tobacco samples comprise six different smokeless tobacco products that were purchased in 2016 by Lab Depot (Atlanta, GA, USA) and shipped to CDC [10]. The four extraction protocols were run in triplicate for each of the six products for a total of  samples. Because the composition of these samples is unknown, it is impossible to distinguish between a zero count that represents the absence of a taxon from the sample specimen and a zero count that represents undersampling. Since zero counts are problematic in compositional methods, we restrict our analyses to the 10 taxa that were detected in all 12 samples of at least one of the six tobacco products. The specific taxa can be found in Supplementary Table S5.
 

The data table contains 105 rows and 88 columns (row names and column names are counted), and mainly consists of two parts. The first part from column 2-79 contains the OTU reads counts of 78 taxa detected by a customized R pipeline and the second part from column 80-88 contains the related metadata information for all 104 samples.


## Code to reproduce the tables/figures in the paper: 
To be added soon. 


