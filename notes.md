Reference paper: https://pmc.ncbi.nlm.nih.gov/articles/PMC6096346/

Workflow:

0. prepare samplesheet
1. import data
2. PCA
   - variances are different to paper
   - clustering is the same / similar
   - could be caused by different scaling methods (R vs scikit), or maybe the paper selected a subset of genes
   - as per the paper "PC analysis was applied to normalized (reads per kilobases of transcript per 1 million mapped reads) and log-transformed count data."
