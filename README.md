# GWASPipeline

A basic 'first-pass' at a GWAS. To run the pipeline, follow the workflow in GWASPipeline.Rmd. There are more thorough descriptions of each step in the Sandpit directory, with relevant references in the References directory. A full working example will be added to the ExampleDatasets directory shortly.

The GWASPipeline does the following:  

  1. QC Genotypes (from either VCF or BCF files)  
  2. Determine the population structure (naive approach currently, to be refined in future)  
  3. perform a standard GWAS using plink  
  4. saves the results of the association tests, produces Q-Q plots and a manhattan plot.  

We assume that the trait files have already been created and QC'd. 
