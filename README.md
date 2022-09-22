# bp219
Data comes from: https://www.ebi.ac.uk/gxa/experiments/E-TABM-734/Downloads?filterFactors=%7B%22COMPARISON_NAME%22%3A%5B%22%5Cu0027heat-killed+Escherichia+coli%5Cu0027+vs+%5Cu0027none%5Cu0027+in+%5Cu0027ulcerative+colitis%5Cu0027%22%5D%7D

This script runs an analysis of the transcriptomic data of the macrophage response to heat-killed E. coli in healthy patients compared to patients with Ulcerative Colitus (UC). Patients with UC have been seen to have stunted inflammatory responses, and this data provides a potential mechanistic explanation as to why that is. 

The script will take in the data reported by the authors and generate barplots showing the x most significant transcriptomic responses where x is a number specified by the user. It also constructs a volcano plot with a p-value threshold line specified by the user.