# Genomics Pipeline Introduction Worksheet

<!--- Write name below --->
## Name: Candice Johnson

<!--- For this worksheet, answer the following questions --->

## Q1: What is a bioinformatics pipeline?
Answer: The use of computer science algorithms to process sequencing data that are later interpreted. 

## Q2: What are the three basic filetypes discussed in this repository? What information do they contain?
Answer:	fastq files, which contain genetic sequences, the quality of the sequences, and their identity
	sam files, which contain genetic sequence, their quality, identity, and mapping information
	vcf files, which contain variant sites, site quality, sample genotypes, and their quality

## Q2: What does a general bioinformatics pipeline look like? Draw a schematic of a pipeline (using boxes and arrows) and add the image file name to the genPipe.jpg text below (png or jpg will work). Your schematic should include file types, program types (e.g., mapping program), and arrows between file types.
![Raw Read FastQC Quality](./genPipe.jpg)

## Q3: Using information from the genomics-pipeline-intro.sh script and [Farkas et al., 2021](https://doi.org/10.3389/fmicb.2021.665041), draw another schematic specific to their study showing file types, program types (use specific program names in this schematic), and arrows between file types. Add the image file name to the sarPipe.jpg text below.
![Raw Read FastQC Quality](./sarPipe.jpg)
I do have another drawing that is more detailed


## Q4: After running the genomics-pipeline-intro.sh script, how many variants are in merged.vcf?
Answer: 1640

## Q5: What is the alternate allele depth of sample SRR11621811|unknown at site 25350 in contig NC_045512.2?
Answer: 798

## Q6: In what ways would you consider filtering the VCF? In other words, what criteria would you use to remove variants / genotypes from the dataset?
Answer: There are many ways to filter the VCF file. You could look at the genotype quality, total depth of a variant site, the overall quality of the site, and allele depth. All of these combined together can give significant data to make a decision to remove specific variants/ genotypes.
