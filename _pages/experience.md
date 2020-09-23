---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: main_bw_crop.jpg
---

# Full-time scientist at Finch Therapeutics
[![Finch](/images/Finch_Short_Logo.png){: .align-left}](https://finchtherapeutics.com/)
_June 2018 - present_  
**Manager:** [Rotem Gura Sadovsky, PhD](https://www.researchgate.net/scientific-contributions/2124564283-Rotem-Gura-Sadovsky)  
**Team Lead:** [Sonia Timberlake, PhD](https://scholar.google.com/citations?user=5vwBXQEAAAAJ&hl=en)
   
I began in my role as a Bioinformatics Research Associate on Finch Therapeutics' Data Science team in June of 2018. As part of the Data Science team, I work in an extensively collaborative environment, combining insights from my teammates, bench scientists and clinicians at Finch to perform high-throughput analysis of multi-omics microbiome data from patients in a variety of disease indications. My role, which was expanded with a promotion Bioinformatics Research Associate II in June of 2020, also means that I assist in computational analysis method development, perform end-to-end implementation and validation of bioinformatics pipelines, and orchestrate meta-analysis projects as part of the Ulcerative Colitis, Crohn's Disease, Autism Spectrum Disorder and Clostridium difficile (CP101) programs.

## Analyzing the human microbiome in IBD
Ulcerative colitis (UC) and Crohn's Disease (CD), collectively form the class of heterogeneous gastrointestinal inflammatory disorders known as inflammatory bowel disease (IBD). As part of the microbial candidate discovery process for in Finch's [Rationally Selected Microbiota](https://finchtherapeutics.com/platform) therapy in IBD, I have reviewed, accessed, and processed data dozens of public and proprietary datasets constituting thousands of samples and billions of reads for meta-analysis. This is involved building and validating version-controlled and scalable bioinformatics pipelines with high-performance parallelized architecture to quality-filter DNA sequences, remove contaminant DNA, and quantify strain abundances using both public and custom databases and methods. After processing was complete, I set out to identify biological features which strongly distinguished IBD and non-IBD cohorts using non-parametric statistics and machine learning. I corrected for correlated patient metadata features, discovered disease location and behavior-specific microbial populations and assessed phylogenetic and functional information to develop hypotheses about the biological mechanisms motivating the observed shifts in the human gut microbiome. In addition to building outstanding technical skills and experience working with high volumes of real-world data under tight deadlines, these projects require that I work independently and effectively communicate my decisions and hypotheses as I assessed data quality, consulted literature for best practices in pipeline construction, and executed on multiple complex projects while effectively communicating my results to scientists, clinicians, and consultants with a variety of backgrounds.

## Computational and scientific skills
With a small group of users and a large number of use cases for Finch's HPC resources, my team and I are the managers and developers of our own infrastructure: as a result, I have become responsible for version-controlled management of multiple pipelines using both Amazon Web Services and Google Cloud Platform architecture. I have spent thousands of hours developing code in Python and bash, as well as constructing pipelines using HPC-specific languages like WDL and SLURM. I examine and manipulate metagenomic and WGS from bacterial and non-bacterial organisms, amassing understanding of the features and caveats of each data type. Technical expertise of this magnitude would have been impossible to build during my undergraduate degree. I am extremely experienced with common data manipulation and visualization libraries like pandas, numpy, seaborn, scipy, and BioPython. At Finch I have worked with hundreds of pieces of software, including but not limited to QIIME, DADA2, mothur, the bioBakery 'omics tools, Robert C. Edgar's tools and their derivatives, bowtie2, KMA, and other mapping software, WDL/Cromwell, phylogenetic manipulation software and packages like SEPP and ete, statistical analysis frameworks and more. I am fortunate to have experienced every point of a experiment's lifecycle: ideation, defining which data the project requires, receiving the data, building and validating a pipeline, examining the results, developing a scientific narrative, and iterating on findings with my coworkers and collaborators.

## Other projects
In addition to the IBD and computational platform development projects, I participate in a variety of activities that utilize my unique skillset at Finch. I optimize experimental procedures by assessing compositions of mock and actual microbial samples under a variety of protocols. I build phylogenetic models to assess 16S rRNA sequencing region specificity and strain abundance in order to guarantee isolation attempts for drug candidate microbes are successful. I construct metrics for identifying significant features in meta-analysis from a variety of contexts, and apply these metrics to actual data.
  


# Carleton College
_2014 - 2018_  
Bachelor of Arts in Biology  
Labs: [Dr. Anderson](https://apps.carleton.edu/people/randerson/), [Dr. Oesper](http://www.cs.carleton.edu/faculty/loesper/)  

My education at Carleton College involved a multidisciplinary combination of biology, chemistry, and computer science. In addition to research with professors in the Computer Science and Biology departments, I was active in the Biology department as a Student Departmental Advisor, tutor, and Biology Stockroom Assistant.
## Anderson lab: 
_May 2017 - June 2018_  
**PI:** [Professor Rika Anderson](https://apps.carleton.edu/people/randerson/)  
Dr. Anderson's studies the co-evolution of microbes and viruses in Earth's oceans. My project focused on relating the evolution of Methanothermococcus species to site-specific geochemical dynamics and interactions with viruses. I annotated open reading frames and prophage/CRISPR loci in 5 single cell _Methanothermococcus_ genomes extracted from the Von Damm vent site [fix this] to identify the differences in functional potential and viral pressure on the strains represented by each genome. Although the core genome of the five strains comprised metabolic functions previously identified in _Methanothermococcus_ archaea, metabolic functions like nitrogen fixation via the _nif_ genes were identified in a subset of the genomes. Hypothesizing that these "accessory" metabolic functions were non-essential and therefore undergoing neutral selection, I aligned metagenomic samples and metatransciptomic samples to each genome and identified the number amino acid variants and single nucleotide variants in each gene. By examining the number of RNA transcripts aligned to each gene alongside the ratio of non-synonymous to synonymous variation, we identified specific functional elements of the accessory genome experiencing variable selection.  
  
The second part of this project involved relating the geochemistry of specific sites to the transcript and variant abundances in each genome. By considering the specific environmental features of each site, we were able to merge our analysis on variable selective pressures with our ideas about how viral predation and vent geochemistry are influencing Methanothermococcus species.

## Oesper lab:
_May 2016 - September 2016_  
**PI:** [Professor Layla Oesper](http://www.cs.carleton.edu/faculty/loesper/)  
In Dr. Oesper's lab, I worked on designing an interface and analysis method for canerous tumor phylogenies reconstructed from ultra-deep sequencing data. I designed this project to enable biological interpretation of the relationships between genes with mutations responsible for the development of blood tumors. Computational tools like [AncesTree](https://doi.org/10.1093/bioinformatics/btv261) reconstruct the progression of clonal states in a tumor's development using single nucleotide mutations and ultra-deep sequencing data. After witnessing tumor phylogeny inference performed with a computational model that would be infeasible through any other means, I began to wonder if computational tools could similarly advance our ability to identify causative biological features from these results. After visualizing the evolution of advanced blood cancers  with phylogenetic trees, I laid the groundwork for these trees to be integrated with known databases of protein interactions in order to develop hypotheses about the biological mechanisms motivating the specific sequence of observed clonal states. This multidisciplinary research project spurred my interest in the intersection between biology and computer science, an interest which lingers to this day.

# Teaching and work-study
## Carleton Prefect Program
Beginning my junior year, I was a prefect in the [Carleton Academic Support Center's Prefect Program(https://www.carleton.edu/prefect-program/about/)]. _Prefects_ are students who attend a class they've taken a in order to provide extracurricular support for students taking the class. As part of the prefect program, I was selected based on an [extensive list of guidelines](https://www.carleton.edu/prefect-program/prefect-job-description/) and trained to facilitate student engagement with course materials via discussion-based prefect sessions I hosted multiple times per week. I orchestrated discussions in groups of up to 50 students to review course content with accompanying study guides, practice sheets, notes, and best practices for reviewing course material. Classes supported:
* BIO126: Energy Flow in Biological Systems (Introductory, 100 student lecture)
* BIO380: Biochemistry (Junior/Senior, 80 student lecture)

## Biology Stockroom
I worked in Carleton's Biology stockroom for my first 2 years of work-study. I prepared media and reagent prep for biology labs, washed too many beakers to count, and performed other activities necessary to keep the Biology department running smoothly.
