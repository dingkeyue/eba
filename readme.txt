Please send an email to ding.keyue@gmail.com to request the file of summary statistics.

The folder contains output from rare-variants based association testing in case_control and trio cohort. qualifying variants were rare functional variants (rv) or HC LoF variants (LoF). 

1. Single-gene based assocation testing for LoF variants grouped by gene was not included since such testing for rare functional variants showed no significant hits (See Figure S1C-D in the manuscript).

2. Results for qualifying variants grouped by pathway in the trio cohort has been present in Figure S3. Only p values were provided in the gskat package.

Directory structure is shown below:

.
├── case_control: 'Rvtests' outputs for the case_control cohort
│   ├── pathway
│   ├── single_gene
│   └── single_variant
└── trio: outputs for the trio cohort
    ├── single_gene: 'rvTDT' output for rare functional variants grouped by gene
    │   ├── pval: pvalue for each gene
    │   └── rvTDT: statistics in performding TDT for each gene
    └── single_variant: 'Plink TDT' output for single variant
