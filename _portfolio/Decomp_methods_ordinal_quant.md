---
title: "Study of Decomposition Methods for Ordinal Quantification"
excerpt: "This is the project I did for my Master's Dissertation.<br/><img src='/images/decomp_ord_quant.png'>"
collection: portfolio
---


This is the project I did for my Master's Dissertation. 

I have a repository on my github page with all the code named [DecompOrdQuant](https://github.com/PerezDavid-98/DecompOrdQuant). 
All the code used is there and a PDF with the full Dissertation (in Spanish)

You can also read the dissertation in my page: [Study of Decomposition Methods for Ordinal Quantification](https://perezdavid-98.github.io/files/Master_Dissertation_Study_of_Decomposition_Methods_For_Ordinal_Quantification.pdf)
It is written in Spanish, but I am currently working on translating it to English. 


The experiment carried out for this dissertation was to check the hypothesis that Decomposition Methods commonly used in Ordinal Classification, are not suitable for Ordinal Quantification problems, specifically the Frank & Hall decomposition method.

The basis of the hypothesis is that this method assumes a homogeneous distribution of classes in cases where they are grouped. This assumption is rarely accurate, causing these methods to perform worse than conventional methods.

To corroborate this hypothesis, two experiments were proposed in which five models widely used in the literature were trained:

* Adjusted Count (AC)
* Probabilistic Adjusted Count (PAC)
* Expectation Maximization (EM)
* Method based on the Hellinger Distance (HDy)
* Method based on the Energy Distance (EDy)

and compared against their counterparts using the F&H decomposition method. 
These experiments not only demonstrated that the decomposition methods are not adequate for ordinal quantification problems, but also refute the assumption of homogeneous distribution in the complementary class during the decomposition process.


More information can be read in the README of the [repository](https://github.com/PerezDavid-98/DecompOrdQuant) and in the [Dissertation](https://perezdavid-98.github.io/files/Master_Dissertation_Study_of_Decomposition_Methods_For_Ordinal_Quantification.pdf) itself.