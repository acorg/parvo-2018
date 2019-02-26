This repo contains FASTA alignments and XML files for BEAST2 for the
*Ancient human parvovirus B19 in Eurasia reveals its long-term association
with humans* PNAS paper.


The `beast` directory contains the XML files used for the BEAST analyses. BEAST2 was used.
* `bmt-new.xml`: XML file. bModelTest analysis.
* `log-bayes-new-m.xml`: XML file. Relaxed lognormal clock, Coalescent Bayesian Skyline population prior.
* `strict-bayes-0-1876-3353-end-n.xml`: XML file. Strict clock, Coalescent Bayesian Skyline population prior. Columns 0-1876 and 3353-end of the alignment (major parent).
* `strict-bayes-1877-3352-n.xml`: XML file. Strict clock, Coalescent Bayesian Skyline population prior. Columns 1877-3352 of the alignment (minor parent).
* `strict-bayes-gt1-new.xml`: XML file. Strict clock, Coalescent Bayesian Skyline population prior. Genotype 1 sequences only.
* `strict-bayes-gt2-new.xml`: XML file. Strict clock, Coalescent Bayesian Skyline population prior. Genotype 2 sequences only.
* `strict-bayes-gt3.xml`: XML file. Strict clock, Coalescent Bayesian Skyline population prior. Genotype 3 sequences only.
* `strict-bayes-gt13.xml`: XML file. Strict clock, Coalescent Bayesian Skyline population prior. Genotype 1 and 3 sequences only.
* `strict-bayes-new.xml`: XML file. Strict clock, Coalescent Bayesian Skyline population prior.
* `ps`: Directory containing the XML files for the path sampling runs.
    * `strict-bayes-new.xml`: XML file. Strict clock, Coalescent Bayesian Skyline population prior.
    * `strict-const-new.xml`: XML file. Strict clock, Coalescent Constant population prior.
    * `strict-exp-new.xml`: XML file. Strict clock, Coalescent Exponential population prior.
* `drt`: Directory containing the XML files for the date randomization test runs.
    * `strict-const-0-n.xml` - `strict-const-4-n.xml`:  XML file. Strict clock, Coalescent Constant population prior. Dates were randomized within all sequences.
    * `strict-const-10-n.xml` - `strict-const-14-n.xml`:  XML file. Strict clock, Coalescent Constant population prior. Dates were randomized within ancient sequences.

The `reads` directory contains the reads that were used to assemble the consensus sequences.

The `consensus` directory contains the consensus sequences.
