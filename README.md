# Block-Forward
Block-Forward Covariate Selection Method


The block-forward (BF) is a method for optimal selection of covariates. 
Briefly, blocks of colinear covariates are considered in a hierarchical order (according to the degree of evidence/impact on the outcome) and, from each block, only the covariate leading to the lowest Akaike Information Criteria (AIC) model is included. Also, such covariate is introduced in the model if and only if all others remain significant.

The BF method is implemented for models of time series of counts, specifically the INGARCH-type models from tscount package in R.
Additionally, this is used in the particular context of the association of hospital admissions and air quality.
Nevertheless, this method for covariate selection can be easily addapted to other models.

There are two files available, one file contains the function with the block-foward method for the INGARCH-type model (forward_tsglm) and the other file contains examples on how to use this function (example_block-forward).

This method is part of the pusblished work: Martins, A., Scotto, M., Deus, R., Monteiro, A., & Gouveia, S. (2021). Association between respiratory hospital admissions and air quality in Portugal: A count time series approach. Plos one, 16(7), e0253455. https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0253455 . Please cite accordingly.
