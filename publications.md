---
layout: page
title: Publications
permalink: /publications/
---

Here you will find a reverse chronological list of all my publications. 

0. Assessing taxonomic metagenome profilers with OPAL

    Fernando Meyer, Andreas Bremges, Peter Belmann, Stefan Janssen, Alice C. McHardy†..., Genome Biology, 2019

    We introduce a framework to compare tools utilized to determine what microbes are present in a sample, and at what relative abundance. This will help computational biologists design better tools to analyze communities of microorganisms (which affect nearly everything in existence!).
    
    [Journal publication](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1646-y) <br />
    [Preprint](https://www.biorxiv.org/content/10.1101/372680v1.article-info)<br />
    [Github repository](https://github.com/CAMI-challenge/OPAL)

0. Toward A Universal Biomedical Data Translator
    
    The Biomedical Data Translator Consortium, Clinical and Translational Science, 2018
    
    The vision and high-level overview of the NIH National Center for Advancing Translational Science (NCATS) project entitled "Translator" (through which we have been funded). The goal of the project is essentially to build a biomedical "Siri": an automated platform for answering biomedical research questions that leverages repositories of publicly available information.
    
    [Journal Article](https://ascpt.onlinelibrary.wiley.com/doi/epdf/10.1111/cts.12591)

0. The Biomedical Data Translator Program: Conception, Culture, and Community
   
    The Biomedical Data Translator Consortium, Clinical and Translational Science, 2018
   
    A description of the NIH NCATS culture that emerged during the Translator project.
    
    [Journal Article](https://ascpt.onlinelibrary.wiley.com/doi/epdf/10.1111/cts.12592)

0. MiCoP: Microbial Community Profiling method for detecting viral and fungal organisms in metagenomic samples
   
    Nathan LaPierre, Serghei Mangul, Mohammed Alswer, Igor Mandric, Nicholas C. Wu,..., BMC Bioinformatics, 2018
   
    We show that read mapping, along with a probabilistic assignment of multi-mapped reads, outperforms other computational approaches to identify the presence and relative amount of viral and fungal organisms in a metagenomic sample of microorganismal DNA.
    
    [Journal publication](https://rdcu.be/bFHkK)<br />
    [BioRxiv](https://www.biorxiv.org/content/early/2018/01/04/243188)

0. Transcriptome analysis in whole blood reveals increased microbial diversity in schizophrenia
   
    Loes M. Olde Loohuis, Serghei Mangul, Anil P. S. Ori, Guillaume Jospin, David..., Nature, Translational Psychiatry, 2018
   
    Along with collaborators at UCLA, we were able to detect a small, but significant amount of microbes in blood. This is surprising since it's typically assumed that the immune system typically removes any microbial presence from human blood. I used a reference-free microbial community algorithm, called EMDeBruijn, to help corroborate the patterns we saw which included an increase in microbial diversity in schizophrenia patients. EMDeBruijn is a metric based on the Wasserstein metric (aka the Earth Mover's Distance) and a de Bruijn graph induced by the k-mers in a metagenomic DNA sample.
    
    [Nature publication](https://www.nature.com/articles/s41398-018-0107-9)<br />
    [BioRiv link](http://biorxiv.org/content/early/2016/06/07/057570)<br />
    [EMDeBruijn](https://github.com/dkoslicki/EMDeBruijn)

0. Improving Min Hash for Metagenomic Classification
   
    Hooman Zabeti and David Koslicki, Submitted to the Journal of Applied Probability, 2017
   
    This work improves upon the so called "min hash" technique (a "probabilistic data analysis" method) to develop a very fast and efficient way to estimate the similarity of two sets of objects (in terms of how much they overlap). The approach we present is orders of magnitude faster (and uses orders of magnitude less space) when two data sets under consideration are of very different size. The kinds of sets we consider are sets of sub-strings (called k-mers) of DNA sequences from communities of microorganisms.
    
    [Article link](https://doi.org/10.1016/j.amc.2019.02.018)<br />
    [BioRxiv link](http://www.biorxiv.org/content/early/2017/09/04/184150)<br />
    [Github Repository](https://github.com/dkoslicki/MinHashMetagenomics)

0. IndeCut evaluates performance of network motif discovery algorithms
   
    Mitra Ansariola, Molly Megraw, David Koslicki, Under review, 2017
   
    A gene regulatory network is basically a representation of how genes interact with each other. In this work, we develop the only (to date) method to assess the accuracy of so called "motif discovery algorithms" that seek to find important sub-networks of a given gene regulatory network. We develop a provably correct mathematical approach (based on a variety of metrics that say how close two matrices are to each other) and use this to assess the performance of a variety of motif discovery algorithms.
    
    [Journal article](https://academic.oup.com/bioinformatics/article/34/9/1514/4721785)<br />
    [BioRxiv preprint](http://www.biorxiv.org/content/early/2017/06/27/156836)<br />
    [Github repository](https://github.com/megrawlab/IndeCut)

0. EMDUnifrac
    
    Jason McClelland and David Koslicki, Journal of Mathematical Biology, 2017
    
    Rapidly answers “why are these data sets different” by leveraging hierarchical/relatedness information. In short, we develop an algorithm to quickly compute the Unifrac distance by leveraging the earth mover's distance, prove its correctness, and derive time and space complexity characterizations.
    
    [Journal article](https://link.springer.com/article/10.1007/s00285-018-1235-9)<br />
    [arXiv link](https://arxiv.org/abs/1611.04634)<br />
    [Github code](https://github.com/dkoslicki/EMDUnifrac)

0. Critical Assessment of Metagenome Interpretation − a benchmark of computational metagenomics software
    
    Alexander Sczyrba, Peter Hofmann, Peter Belmann, David Koslicki, Stefan Janssen,..., Accepted to Nature Methods, 2017
    
    In a very reproducible fashion, we assess a wide variety of computational techniques in metagenomics, including assembly (putting together pieces of genomes, called contigs, from short reads), binning (figuring out where the contigs came from), and taxonomic profiling (determining which organisms are present in a sample and at what relative amount).
    
    [Nature publication](https://www.nature.com/articles/nmeth.4458)<br />
    [bioRxiv link](http://biorxiv.org/content/early/2017/01/09/099127)<br />
    [Github repository](https://github.com/CAMI-challenge)

0. Substitution Markov chains and Martin boundaries
    
    David Koslicki and Manfred Denker, Rocky Mountain Journal of Mathematics, 2016
    
    After introducing the notion of a random substitution Markov chain, we relate it to other notions of a "random substitution" and give a complete description of the Martin boundary for a few interesting examples.
    
    [Journal article](http://projecteuclid.org/euclid.rmjm/1483520434)<br />
    [Preprint](https://arxiv.org/abs/1705.10830)

0. Exact probabilities for the indeterminacy of complex networks as perceived through press perturbations
    
    David Koslicki and Mark Novak, Accepted to The Journal of Mathematical Biology (DOI: 10.1007/s00285-017-1163-0), 2016
    
    In a network of interacting quantities (such as a food web), we examine how qualitative and quantitative predictions change when a quantity (such as the abundance of an organism or a set of organisms) is increased. This is quantified in terms of which model parameters cause the largest change in predictions.
    
    [Journal Article](http://rdcu.be/uo2t)<br />
    [BioRxiv link](http://biorxiv.org/content/early/2016/10/25/083089)

0. Reference-free comparison of microbial communities via de Bruijn graphs
    
    David Koslicki and Serghei Mangul, ACM-BCB, 2016
    
    We present the idea of using the "earth mover's distance" (aka the first Wasserstein metric) to measure the distance between samples of DNA. This reduces to finding the most efficient way to transform one kind of graph (known as de Bruijn graphs) into another.
    
    [Conference proceedings](http://dl.acm.org/citation.cfm?id=2975167)<br />
    [BioRxiv link](http://biorxiv.org/content/early/2016/05/24/055020)<br />
    [Github repository](https://github.com/dkoslicki/EMDeBruijn)

0. MetaPalette: A K-mer painting approach for metagenomic taxonomic profiling and quantification of novel strain variation
    
    David Koslicki and Daniel Falush, mSystems, 2016
    
    We present a computational technique that answers the question "Which organisms are present in a given sample of of DNA from a microbial community, and at what relative amount" while simultaneously predicting the relatedness of novel (never-before seen organisms) in relation to known organisms. This relies on a mathematical technique referred to as sparsity-promoting optimization and relies on a technique similar to the Jaccard index.
    
    [Journal article](http://msystems.asm.org/content/1/3/e00020-16)<br />
    [BioRxiv link](http://biorxiv.org/content/early/2016/02/17/039909)<br />
    [Github repository](https://github.com/dkoslicki/MetaPalette)

0. ARK: Aggregation of Reads by K-Means for Estimation of Bacterial Community Composition
    
    David Koslicki, Saikat Chatterjee, Damon Shahrivar, Alan W. Walker, Suzanna C...., PLoS ONE, 2015
    
    We develop a pre-processing step that significantly improves k-mer based metagenomic profiling techniques.
    
    [Journal article](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0140644)<br />
    [Preprint link](https://koslicki.math.oregonstate.edu/sites/koslicki.math.oregonstate.edu/files/ARKCombined.pdf)<br />
    [Github code](https://github.com/dkoslicki/ARK)

0. SEK: sparsity exploiting k-mer-based estimation of bacterial community composition
    
    Saikat Chatterjee, David Koslicki, Siyuan Dong, Nicolas Innocenti, Lu Cheng, Yueheng..., Oxford Journal of Bioinformatics, 2014
    
    In this paper, we improve both the accuracy and speed of the Quikr approach to classifying a given set of metagenomic DNA sequences (16S rRNA). This is accomplished by increasing the number of "feature vectors" we use for each training genome, and by modifying the Lawson-Hanson algorithm for non-negative least squares.
    
    [Journal article](https://doi.org/10.1093/bioinformatics/btu320)<br />
    [arXiv link](https://arxiv.org/abs/1407.0387)<br />
    [Github repository](https://github.com/dkoslicki/SEK)

0. WGSQuikr: fast whole-genome shotgun metagenomic classification
    
    David Koslicki, Simon Foucart, and Gail Rosen, PLoS ONE, 2014
    
    Extending the results of Quikr to whole genome shotgun metagenomic samples, we develop a method to automatically select a parameter that balances sparsity (how succinct the result is) with accuracy.
    
    [Journal article](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0091784)<br />
    [Preprint](https://koslicki.math.oregonstate.edu/sites/koslicki.math.oregonstate.edu/files/WGSQuikr_final.pdf)<br />
    [Sourceforge repository](https://sourceforge.net/projects/wgsquikr/)

0. Sparse recovery by means of nonnegative least squares
    
    Simon Foucart and David Koslicki, IEEE Signal Processing Letters, 2014
    
    We prove that nonnegative least squares (typically prone to over-fitting) can be slightly modified to return sparse results.
    
    [Journal article](http://ieeexplore.ieee.org/document/6750023/?arnumber=6750023)<br />
    [Preprint](https://koslicki.math.oregonstate.edu/sites/koslicki.math.oregonstate.edu/files/SRasNNLS_final.pdf)<br />
    [Reproducibles](http://math.oregonstate.edu/~koslickd/SRasNNLS_reproducibles.zip)

0. Coding sequence density estimation via topological pressure
    
    David Koslicki and Daniel J. Thompson, Journal of Mathematical Biology, 2014
    
    We demonstrate that a concept of "weighted information content" (known as topological pressure, from the ergodic theory literature) can be used to facilitate the analysis of genomic data (in particular, find areas of a genome that have many genes in them). This is a conceptual extension to topological entropy approach presented earlier.
    
    [Journal article](https://link.springer.com/article/10.1007/s00285-014-0754-2/fulltext.html)<br />
    [arXiv link](https://arxiv.org/abs/1109.5999)<br />
    [Sourceforge repository](https://sourceforge.net/projects/topologicalpres/)

0. On entropy-based data mining
    
    Andreas Holzinger, Matthias Hörtenhuber, Christopher Mayer, Martin Bachler,..., Chapter, Interactive Knowledge Discovery and Data Mining in Biomedical Informatics, 2014
    
    We review a variety of entropy/randomness-based techniques that are useful in a variety of data mining applications.
    
    [Chapter](https://link.springer.com/chapter/10.1007/978-3-662-43968-5_12)<br />
    [Preprint](https://www.dropbox.com/s/n5rtbytvtudocqx/Combined.pdf?dl=0)

0. Quikr: a method for rapid reconstruction of bacterial communities via compressive sensing
    
    David Koslicki, Simon Foucart, and Gail Rosen, Oxford Journal of Bioinformatics, 2013
    
    We introduce an extremely fast, light-weight, "big data" algorithm to quickly answer the question of "which bacteria are present?" in a given sample of DNA. The method is based on the theory of compressed sensing and aims to find the simplest explanation for the data in terms of known information.
    
    [Journal article](https://doi.org/10.1093/bioinformatics/btt336)<br />
    [Preprint link](https://www.dropbox.com/s/8izc82bzsbzl50j/QuikrRevisionPrePrint.pdf?dl=0)<br />
    [Github repository](https://github.com/dkoslicki/Quikr) (see also [https://github.com/dkoslicki/CAMIARKQuikr](https://github.com/dkoslicki/CAMIARKQuikr))

0. Dissertation
    
    David Koslicki, Penn State University, 2012
    
    This is my PhD thesis from Penn State (advised by Manfred Denker).
    
    [Penn State Dissertation Repository](https://etda.libraries.psu.edu/catalog/14024)<br />
    [Dissertation link](https://www.dropbox.com/s/qyrt7ju6x57qpjb/DavidKoslicki-Dissertation.pdf?dl=0)<br />

0. Topological entropy of DNA sequences
    
    David Koslicki, Oxford Journal of Bioinformatics, 2011
    
    I define a new notion of "randomness" (called topological pressure) suitable for use on sequences of symbols (words) of finite length. I show that this can be used to distinguish between biologically interesting sequences in the human genome.

    [Journal article](https://doi.org/10.1093/bioinformatics/btr077) <br />
    [arXiv link](https://arxiv.org/abs/1101.4636)
{: reversed="reversed"}

