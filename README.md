# Slides for the "preciseTAD: A machine learning framework for precise 3D domain boundary prediction at base-level resolution" workshop @ EuroBioc2020

The [preciseTADworkshop](https://github.com/dozmorovlab/preciseTADworkshop) introduces methods for transforming the identification of boundaries that demarcate Topologically Associating Domains (TADs)-- referred to as TAD-calling--into a supervised machine learning framework. Chromosome conformation capture technologies combined with high-throughput sequencing (Hi-C) have revealed that chromatin undergoes layers of compaction through DNA looping and folding, forming dynamic 3-dimensional (3D) structures. Among these are TADs, which are known to play critical roles in cell dynamics like gene regulation and cell differentiation. However, precise TAD-calling remains difficult, as it is strongly reliant on Hi-C data resolution. Obtaining genome-wide chromatin interactions at high-resolution is costly resulting in low resolution of Hi-C matrices and high uncertainty in the location of domain boundaries. In this workshop we will circumvent this resolution restriction by building predictive models that leverage high resolution functional genomic element data (ChIP-seq). As an application, we will demonstrate that these methods provide more precise boundary detection compared to a conventional TAD-calling algorithm by evaluating a variety of visualization techniques in relation to the enrichment of key molecular drivers of 3D chromatin. The methods discussed in this workshop will give users tools for bridging the resolution gap between 1D ChIP-seq annotations and 3D Hi-C sequencing data for more precise and biologically meaningful boundary identification.

This workshop is based on [Spiro C. Stilianoudakis, Mikhail G. Dozmorov; "preciseTAD: A machine learning framework for precise 3D domain boundary prediction at base-level resolution"](https://doi.org/10.1101/2020.09.03.282186). 

Key materials for the workshop: 

- [Slides with a brief introduction for the workshop](https://stilianoudakis.github.io/slides_preciseTADworkshop/#1)
- [preciseTADworkshop GitHub repo](https://github.com/dozmorovlab/preciseTADworkshop)
- [preciseTADworkshop Docker image](https://hub.docker.com/repository/docker/stilianoudakis/precisetadworkshop)
- [preciseTADworkshop pkgdown website](https://dozmorovlab.github.io/preciseTADworkshop/)

This workshop will be presented at the [Bioconductor Virtual Conference 2020](https://bioc2020.bioconductor.org/), December 16th, 2020, 11:30 AM - 12:15 PM
