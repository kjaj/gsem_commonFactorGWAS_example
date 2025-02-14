# gsem_commonFactorGWAS_example
example code for running common factor gwas using genomicsem

rough order:

1. make filelists (and make a set of sumstats each split by chrom if needed)
2. run multivariable ldsc (NOTE - you need to have sumstats already munged)
3. run sumstats function
4. run commonfactor gwas (no snps)
5. run commonfactor gwas (snps)


*nb with queueing - since GWAS is run per chrom this can be split into separate jobs (each with separate associated .sh script) rather than in a loop like this, same with sumstats function queueing
