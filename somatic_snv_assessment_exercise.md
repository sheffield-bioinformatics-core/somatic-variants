---
title: "Exercise: Assessing and Evaluating SNV Calls"
author: "Matt Eldridge and Mark Dunning"
date: "July 2017"
output: html_document
---

### Introduction

The purpose of this practical is to get you familiar with visualising somatic SNV calls in IGV, and to assess whether they are genuine calls or technical artefacts. 

You might find this [set of hints](https://rawgit.com/bioinformatics-core-shared-training/cruk-summer-school-2017/master/Day3/somatic_snv_assessment_igv_tips.html) useful when assessing the calls.

### Preparation

This section uses a breast cancer genome that is publicly-available and well-characterised

- http://www.pawefish.path.cam.ac.uk/BreastCellLineDescriptions/HCC1143.html
- https://cansar.icr.ac.uk/cansar/cell-lines/HCC1143/copy_number_variation/

It was used as part of the Cancer Research Uk Cambridge Institute Summer School "Analysis of Cancer Genomes"; the material for which can be [accessed online](https://bioinformatics-core-shared-training.github.io/cruk-summer-school-2017/). The files you will need for this section are available in the google drive (make sure to download the `bai` files that correspond to the `bam` files)

Open the IGV genome browser.

* Load the Tumour `.bam` file `HCC1143_subset.bam`

* Load the Normal `.bam` file `HCC1143_BL_subset.bam`

* Load the `.vcf` file containing variants called by Caveman for this tumour /normal pair `HCC1143_vs_HCC1143_BL.annot.muts.vcf.gz`

* Load annotations from the IGV server by choosing `Load from Server...` from the `File` menu
    * Select the `dbSNP` and `Repeat Masker` options within the `Variation and Repeats` annotations section

All but one of the following set of candidate somatic SNVs were called by CaVEMan. The VCF track shows whether the call was made by CaVEMan; hovering over the bar representing the call will bring up a tooltip with details of the SNV call including whether it was filtered.

Click on the `IGV` link for each variant in turn to navigate to that genomic location in the IGV browser. Review the read alignments supporting the variant and those in the region surrounding the variant to decide on your confidence in the call. Click on the `Vote` link to register your decision anonymously.

### Candidate SNVs

<div style="line-height: 50%;"><br></div>

1. chr8:142486034 C>T
    * [IGV](http://localhost:60151/goto?locus=8:142486034)
    * <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLSdSZ2QZyaimbPBwEcuo4FkGfzf6envyie26BXPJYpabQbVMuw/viewform">Vote</a>

<div style="line-height: 20%;"><br></div>

2. chr19:14860710 C>T
    * [IGV](http://localhost:60151/goto?locus=19:14860710)
    * <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLSfi9asi-4LM0BOhA_e_-A-FxP-hmYPdFg1S5RJ74PZ-5r5nKw/viewform">Vote</a>

<div style="line-height: 20%;"><br></div>

3. chr8:50114475 T>G
    * [IGV](http://localhost:60151/goto?locus=8:50114475)
    * <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLSckoLOkT4Nvu2iBwLV4U8NLWd2VwGP0mextMq2Ma0as0WDGuA/viewform">Vote</a>

<div style="line-height: 20%;"><br></div>

4. chr3:45153669 C>A
    * [IGV](http://localhost:60151/goto?locus=3:45153669)
    * <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLSfNmlkAfF0Jnk4s6Cgg65J5HUyzf5bkAzPCUiJk3ujgdU7lAg/viewform">Vote</a>

<div style="line-height: 20%;"><br></div>

5. chr1:169147080 T>G
    * [IGV](http://localhost:60151/goto?locus=1:169147080)
    * <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLScWmJl65TqN0yxDWK_itUNtWeQwjMIslTipd3UVKMjM_76BMg/viewform">Vote</a>

<div style="line-height: 20%;"><br></div>

6. chr14:106457339 T>C
    * [IGV](http://localhost:60151/goto?locus=14:106457339)
    * <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLSdjnS8tiMyw0P8j_UX_35EhG4E62pTZhWXyWFBfvkLWA3xEyQ/viewform">Vote</a>

<div style="line-height: 20%;"><br></div>

7. chr7:140934248 G>A
    * [IGV](http://localhost:60151/goto?locus=7:140934248)
    * <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLSeUIfwE3ylcFwL_HSVv23NvfKTNygPHPpUho3IBu902orIwRw/viewform">Vote</a>

<div style="line-height: 20%;"><br></div>

8. chr4:22961617 A>T
    * [IGV](http://localhost:60151/goto?locus=4:22961617)
    * <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLSfCmFru9y9gYG9jsr30t4rVgoyavSPOSgggH3c4YEgpVlk0zA/viewform">Vote</a>

<div style="line-height: 100%;"><br></div>
