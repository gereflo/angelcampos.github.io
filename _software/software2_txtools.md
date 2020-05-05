---
title: "txtools"
excerpt: "An R package that processes GenomicAlignments into their transcriptomic versions."
collection: software
---

**txtools** is a package that processes GenomicAlignments objects into
their transcriptomic versions.

**txtools** is meant to expand the functionality of the
[**GenomicAlignments**](https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html)
package, as currently it does not support transcriptomic-wise features.

Transcriptomic-wise features are increasingly needed
to process and analyze RNA-seq data in which transcript-structure and
close nucleotide-level inspection is required, e.g. analyzing
RNA-seq data derived from RNA-modifications detection protocols.

## Installation

You can install the development version from
[GitHub](https://github.com/AngelCampos/txtools) with:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("AngelCampos/txtools")
```

# Demo

You can also find a demo of txtools in its [**GitHub page**](https://github.com/AngelCampos/txtools).

In it you will load a BAM file of human data and convert to their transcriptomic
counterparts, to see how easy analyzing and visualizing RNA-seq data can get 
using txtools.
