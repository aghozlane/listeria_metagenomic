# listeria_metagenomic

For files are provided :
 - The count matrix corresponds to the number of amplicons mapped per OTU for each sample
 - The annotation matrix corresponds to the taxonomical annotation of each OTU
 - The target matrix provides the experimental design
 - The contrast file correspond to the deseq2 model
These data can be re-analysed and visualize with shaman.cb3i.pasteur.fr.
Warning : It is nessary to indicate as interaction in this exact order :
 1. condition:mice
 2. condition:time

Of note: 
- Reads data are provided here : http://www.ebi.ac.uk/ena/data/view/PRJEB13646
- "m" samples correspond to T0 samples that were obtained by adding 2 Day and 1 Day before infection counts as following
WT.m2:
WT2.2
WT2.20

WT.m3:                                                                           
WT3.3
WT3.21

WT.m4                                                                            
WT4.4
WT4.22

WT.m5                                                                            
WT5.5

Delta.m7                                                                         
Delta1.7
Delta1.25                                                                    

Delta.m8                                                                         
Delta2.8
Delta2.26

Delta.m9                                                                         
Delta3.9
Delta3.27

Delta.m11                                                                        
Delta5.11
Delta5.29

Delta.Compl.m13                                                                  
Delta.Compl1.13
Delta.Compl1.31

Delta.Compl.m15                                                                  
Delta.Compl3.15
Delta.Compl3.33

Delta.Compl.m16                                                                  
Delta.Compl4.16
Delta.Compl4.34

Delta.Compl.m17                                                                  
Delta.Compl5.17
Delta.Compl5.29
