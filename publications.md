---
layout: page
title: Publications
permalink: /publications/
---

Here you will find a reverse chronological list of all my publications. 

0. Assessing taxonomic metagenome profilers with OPAL

    Fernando Meyer, Andreas Bremges, Peter Belmann, Stefan Janssen, Alice C. McHardy†... , Genome Biology , Monday, March 4, 2019

    We introduce a framework to compare tools utilized to determine what microbes are present in a sample, and at what relative abundance. This will help computational biologists design better tools to analyze communities of microorganisms (which affect nearly everything in existence!).
    
    Journal publication <br />
    Preprint<br />
    Github repository

0. Toward A Universal Biomedical Data Translator
    
    The Biomedical Data Translator Consortium , Clinical and Translational Science , Friday, November 9, 2018
    
    The vision and high-level overview of the NIH National Center for Advancing Translational Science (NCATS) project entitled "Translator" (through which we have been funded). The goal of the project is essentially to build a biomedical "Siri": an automated platform for answering biomedical research questions that leverages repositories of publicly available information.
    
    Journal Article

0. The Biomedical Data Translator Program: Conception, Culture, and Community
   
    The Biomedical Data Translator Consortium , Clinical and Translational Science , Friday, November 9, 2018
   
    A description of the NIH NCATS culture that emerged during the Translator project.
    
    Journal Article

0. MiCoP: Microbial Community Profiling method for detecting viral and fungal organisms in metagenomic samples
   
    Nathan LaPierre, Serghei Mangul, Mohammed Alswer, Igor Mandric, Nicholas C. Wu,... , BMC Bioinformatics , Thursday, November 1, 2018
   
    We show that read mapping, along with a probabilistic assignment of multi-mapped reads, outperforms other computational approaches to identify the presence and relative amount of viral and fungal organisms in a metagenomic sample of microorganismal DNA.
    
    Journal publication<br />
    Biorxiv

0. Transcriptome analysis in whole blood reveals increased microbial diversity in schizophrenia
   
    Loes M. Olde Loohuis, Serghei Mangul, Anil P. S. Ori, Guillaume Jospin, David... , Nature, Translational Psychiatry , Friday, May 11, 2018
   
    Along with collaborators at UCLA, we were able to detect a small, but significant amount of microbes in blood This is surprising since it's typically assumed that the immune system typically removes any microbial presence from human blood. I used a reference-free microbial community algorithm, called EMDeBruijn, to help corroborate the patterns we saw which included an increase in microbial diversity in schizophrenia patients. EMDeBruijn is a metric based on the Wasserstein metric (aka the Earth Mover's Distance) and a de Bruijn graph induced by the k-mers in a metagenomic DNA sample.
    
    Nature publication<br />
    BioArXiv link<br />
    EMDeBruijn

0. Improving Min Hash for Metagenomic Classification
   
    Hooman Zabeti and David Koslicki , Submitted to the Journal of Applied Probability , Tuesday, July 4, 2017
   
    This work improves upon the so called "min hash" technique (a "probabilistic data analysis" method) to develop a very fast and efficient way to estimate the similarity of two sets of objects (in terms of how much they overlap). The approach we present is orders of magnitude faster (and uses orders of magnitude less space) when two data sets under consideration are of very different size. The kinds of sets we consider are sets of sub-strings (called k-mers) of DNA sequences from communities of microorganisms.
    
    Article link<br />
    BioRxiv link<br />
    Github Repository

0. IndeCut evaluates performance of network motif discovery algorithms
   
    Mitra Ansariola, Molly Megraw, David Koslicki , Under review , Sunday, July 2, 2017
   
    A gene regulatory network is basically a representation of how genes interact with each other. In this work, we develop the only (to date) method to assess the accuracy of so called "motif discovery algorithms" that seek to find important sub-networks of a given gene regulatory network. We develop a provably correct mathematical approach (based on a variety of metrics that say how close two matrices are to each other) and use this to assess the performance of a variety of motif discovery algorithms.
    
    Journal article<br />
    BioRxiv preprint<br />
    Github repository

0. EMDUnifrac
    
    Jason McClelland and David Koslicki , Journal of Mathematical Biology , Sunday, January 1, 2017
    
    Rapidly answers “why are these data sets different” by leveraging hierarchical/relatedness information. In short, we develop an algorithm to quickly compute the Unifrac distance by leveraging the earth mover's distance, prove its correctness, and derive time and space complexity characterizations.
    
    Journal article<br />
    arXiv link<br />
    Github code

0. Critical Assessment of Metagenome Interpretation − a benchmark of computational metagenomics software
    
    Alexander Sczyrba, Peter Hofmann, Peter Belmann, David Koslicki, Stefan Janssen,... , Accepted to Nature Methods , Sunday, January 1, 2017
    
    In a very reproducible fashion, we assess a wide variety of computational techniques in metagenomics, including assembly (putting together pieces of genomes, called contigs, from short reads), binning (figuring out where the contigs came from), and taxonomic profiling (determining which organisms are present in a sample and at what relative amount).
    
    Nature publication<br />
    bioRxiv link<br />
    Github repository

0. Substitution Markov chains and Martin boundaries
    
    David Koslicki and Manfred Denker , Rocky Mountain Journal of Mathematics , Tuesday, November 1, 2016
    
    After introducing the notion of a random substitution Markov chain, we relate it to other notions of a "random substitution" and give a complete description of the Martin boundary for a few interesting examples.
    
    Journal article<br />
    Preprint

0. Exact probabilities for the indeterminacy of complex networks as perceived through press perturbations
    
    David Koslicki and Mark Novak , Accepted to The Journal of Mathematical Biology (DOI: 10.1007/s00285-017-1163-0) , Saturday, October 1, 2016
    
    In a network of interacting quantities (such as a food web), we examine how qualitative and quantitative predictions change when a quantity (such as the abundance of an organism or a set of organisms) is increased. This is quantified in terms of which model parameters cause the largest change in predictions.
    
    Journal Article<br />
    BioRxiv link

0. Reference-free comparison of microbial communities via de Bruijn graphs
    
    David Koslicki and Serghei Mangul , ACM-BCB , Tuesday, May 24, 2016
    
    We present the idea of using the "earth mover's distance" (aka the first Wasserstein metric) to measure the distance between samples of DNA. This reduces to finding the most efficient way to transform one kind of graph (known as de Bruijn graphs) into another.
    
    Conference proceedings<br />
    BioRxiv link<br />
    Github repository

0. MetaPalette: A K-mer painting approach for metagenomic taxonomic profiling and quantification of novel strain variation
    
    David Koslicki and Daniel Falush , mSystems , Wednesday, February 17, 2016
    
    We present a computational technique that answers the question "Which organisms are present in a given sample of of DNA from a microbial community, and at what relative amount" while simultaneously predicting the relatedness of novel (never-before seen organisms) in relation to known organisms. This relies on a mathematical technique referred to as sparsity-promoting optimization and relies on a technique similar to the Jaccard index.
    
    Journal article<br />
    BioRxiv link<br />
    Github repository

0. ARK: Aggregation of Reads by K-Means for Estimation of Bacterial Community Composition
    
    David Koslicki, Saikat Chatterjee, Damon Shahrivar, Alan W. Walker, Suzanna C.... , PLoS ONE , Friday, October 23, 2015
    
    We develop a pre-processing step that significantly improves k-mer based metagenomic profiling techniques.
    
    Journal article<br />
    Preprint link<br />
    Github code

0. SEK: sparsity exploiting k-mer-based estimation of bacterial community composition
    
    Saikat Chatterjee, David Koslicki, Siyuan Dong, Nicolas Innocenti, Lu Cheng, Yueheng... , Oxford Journal of Bioinformatics , Wednesday, May 7, 2014
    
    In this paper, we improve both the accuracy and speed of the Quikr approach to classifying a given set of metagenomic DNA sequences (16S rRNA). This is accomplished by increasing the number of "feature vectors" we use for each training genome, and by modifying the Lawson-Hanson algorithm for non-negative least squares.
    
    Journal article<br />
    arXiv link<br />
    Github repository

0. WGSQuikr: fast whole-genome shotgun metagenomic classification
    
    David Koslicki, Simon Foucart, and Gail Rosen , PLoS ONE , Thursday, March 13, 2014
    
    Extending the results of Quikr to whole genome shotgun metagenomic samples, we develop a method to automatically select a parameter that balances sparsity (how succinct the result is) with accuracy.
    
    Journal article<br />
    Preprint<br />
    Sourceforge repository

0. Sparse recovery by means of nonnegative least squares
    
    Simon Foucart and David Koslicki , IEEE Signal Processing Letters , Thursday, February 27, 2014
    
    We prove that nonnegative least squares (typically prone to over-fitting) can be slightly modified to return sparse results.
    
    Journal article<br />
    Preprint<br />
    Reproducibles

0. Coding sequence density estimation via topological pressure
    
    David Koslicki and Daniel J. Thompson , Journal of Mathematical Biology , Wednesday, January 22, 2014
    
    We demonstrate that a concept of "weighted information content" (known as topological pressure, from the ergodic theory literature) can be used to facilitate the analysis of genomic data (in particular, find areas of a genome that have many genes in them). This is a conceptual extension to topological entropy approach presented earlier.
    
    Journal article<br />
    arXiv link<br />
    Sourceforge repository

0. On entropy-based data mining
    
    Andreas Holzinger, Matthias Hörtenhuber, Christopher Mayer, Martin Bachler,... , Chapter, Interactive Knowledge Discovery and Data Mining in Biomedical Informatics , Wednesday, January 1, 2014
    
    We review a variety of entropy/randomness-based techniques that are useful in a variety of data mining applications.
    
    Chapter<br />
    Preprint

0. Quikr: a method for rapid reconstruction of bacterial communities via compressive sensing
    
    David Koslicki, Simon Foucart, and Gail Rosen , Oxford Journal of Bioinformatics , Thursday, June 20, 2013
    
    We introduce an extremely fast, light-weight, "big data" algorithm to quickly answer the question of "which bacteria are present?" in a given sample of DNA. The method is based on the theory of compressed sensing and aims to find the simplest explanation for the data in terms of known information.
    
    Journal article<br />
    Preprint link<br />
    Github repository (see also [https://github.com/dkoslicki/CAMIARKQuikr](https://github.com/dkoslicki/CAMIARKQuikr))

0. Dissertation
    
    David Koslicki , Penn State University , Tuesday, May 1, 2012
    
    This is my PhD thesis from Penn State (advised by Manfred Denker).
    
    Penn State Dissertation Repository<br />
    Dissertation link<br />
    Topological entropy of DNA sequences
    
0. David Koslicki , Oxford Journal of Bioinformatics , Monday, February 21, 2011
    
    I define a new notion of "randomness" (called topological pressure) suitable for use on sequences of symbols (words) of finite length. I show that this can be used to distinguish between biologically interesting sequences in the human genome.

    Journal article <br />
    arXiv link
{: reversed="reversed"}

