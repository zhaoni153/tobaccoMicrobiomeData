# 16s rRNA sequencing data from mock communities and real tobacco samples

---
Ni Zhao (nzhao10@jhu.edu), Mo Li (mli171@jhu.edu), Glen Satten (GSatten@emory.edu)
---
## Overview
The github page contains the 16s rRNA sequencing data that are used in our paper <br/>
What Can We Learn about the Bias of Microbiome Studies from Analyzing Data from Mock Communities? Li, M., Tyx, R.E., Rivera, A.J., Zhao, N., Satten, G.A., *Genes*, In press  <br/>

## Details

This study used data from 4 different types of samples: the Zymo standard comprising cells (ZMC); the Zymo cell standard mixed with a biological matrix (ZMC + Matrix); samples of Swedish Snus, a smokeless tobacco product from Sweden that has been pasteurized; and samples comprising commercially available smokeless tobacco products. 
Samples were processed by four extraction protocols: Protocol 1 (Base) serves as a baseline method, Protocols 2 (Enzymes), 3 (Lifeguard®) and 4 (RNAProtect®) can be considered as modifications of the Base method, which all aim at improving the DNA extraction efficacy by facilitating the bacterial lysis or by providing 

.  and is a modification of a protocol that has been previously described by us [12], but without the use of any additional enzymes. The other three protocols can be considered as modifications of the base method. Protocol 2 (Enzymes) is our original protocol, which here we describe as the base protocol but with added enzymes to facilitate bacterial lysis; to 2.5 mL of bead solution in the extraction tube, we added 62.5 µL of an enzyme cocktail containing 12.5 µL lysozyme (10 mg/mL), 37.5 µL mutanolysin (1 mg/mL) and 12.5 µL lysostaphin (5 mg/mL). We then vortexed briefly and incubated at 37 °C for 30 min before adding 50 µL proteinase K (from a 20 mg/mL stock solution), 0.25 mL of solution SR1 and 0.8 mL of solution SR2, incubating for another 30 min at 55 °C, and then proceeded with the MoBio extraction protocol. Protocol 3 (Lifeguard®) followed the baseline protocol, but added Lifeguard® Soil Preservation Reagent (Qiagen, Germantown, MD, USA, formerly MoBio, Carlsbad, CA, USA) prior to extraction, using 1 mL Lifeguard® per 0.5 g tobacco sample. Protocol 4 (RNAProtect®) also followed the baseline protocol, but added RNAProtect® Bacterial Reagent (Qiagen, Germantown, MD, USA) prior to extraction, using 1 mL RNAProtect® per 0.5 g tobacco sample. 
The ZMC samples are constructed with a known (theoretical) composition. For the samples we analyzed, the theoretical compositions provided by Zymo based on kit batch number is: Staphylococcus—13.3%, Bacillus—15.7%, Lactobacillus—18.8%, Listeria—15.9%, Enterococcus—10.4%, Salmonella—11.3%, Escherichia Shigella—10.0%, Pseudomonas—4.6% (Zymo, personal communication). To create the ZMC + Matrix samples, a 75 µL volume of the ZMC solution was pipetted directly onto a 0.5 g snus tobacco sample and vortexed for 30 s. Before continuing with extractions, a 10 min incubation at room temperature was executed to allow complete absorption of ZMC microbes onto the snus substrate, to better simulate a real tobacco product. Sample processing of the tobacco samples is as described in Tyx et al. (2022) [10].
Each sample was analyzed using all four protocols; in addition, we conducted replicate extractions of each sample. For the ZMC, ZMC + Matrix and Swedish Snus data we performed four replicate extractions for each protocol; thus, these sample sets each have 16 observations. The smokeless tobacco samples comprise six different smokeless tobacco products that were purchased in 2016 by Lab Depot (Atlanta, GA, USA) and shipped to CDC [10]. The four extraction protocols were run in triplicate for each of the six products for a total of  samples. Because the composition of these samples is unknown, it is impossible to distinguish between a zero count that represents the absence of a taxon from the sample specimen and a zero count that represents undersampling. Since zero counts are problematic in compositional methods, we restrict our analyses to the 10 taxa that were detected in all 12 samples of at least one of the six tobacco products. The specific taxa can be found in Supplementary Table S5.
![image](https://user-images.githubusercontent.com/7673340/192787718-015bf40f-4d39-43ce-92e3-cd3dd6a5c8eb.png)

This data table comes from 3 different types of samples: the Zymo standard comprising cells (ZMC); the Zymo cell standard mixed with a biological matrix (ZMC + Matrix); and samples comprising commercially available smokeless tobacco products. Each samples was analyzed using the four different DNA extraction protocols, Base, Enzymes, Lifeguard and RNAProtect. 

The data table contains 105 rows and 88 columns (row names and column names are counted), and mainly consists of two parts. The first part from column 2-79 contains the OTU reads counts of 78 taxa detected by a customized R pipeline and the second part from column 80-88 contains the related metadata information for all 104 samples.


## Code to reproduce the tables/figures in the paper: 
To be added soon. 


