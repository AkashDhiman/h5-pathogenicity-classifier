## Description

This code replicates the model discussed in the following research  
> A. Chadha, R. Dara and Z. Poljak, "Convolutional Classification of Pathogenicity in H5 Avian Influenza Strains," 2019 18th IEEE International Conference On Machine Learning And Applications (ICMLA), Boca Raton, FL, USA, 2019, pp. 1570-1577.
    
- Within research 1202 HP sequences, 1167 LP sequences were used which were gathered from various sources such as https://www.fludb.org
- This code has yet to collect relevant number of data and works with only 133 HP sequences and 750 LP sequences
- These sequences were collected from https://www.fludb.org only
- They are all HA segments of H5 avian influenza virus of various kinds
- These HA segments are aligned using MUSCLE (Multiple Sequence Comparison by Log-Expectation) algorithm, available [here](https://www.fludb.org/brc/msa.spg?method=ShowCleanInputPage&decorator=influenza)
