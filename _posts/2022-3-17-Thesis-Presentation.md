---
layout: post
title: Data Analysis and Software Design to Assist Researchers in Choosing Effective Endogenous Genes
for CRISPRa
---
***Master's Thesis.*** *March 17, 2022*
<br>
*By Joely Nelson*

My thesis project. CRISPR activation (CRISPRa) is a tool used in synthetic biology to activate genes. However, there are stringent rules for where CRISPRa can effectively promote transcription. Many of these rules are either unknown or have not been compiled into a single model. In order to rectify this, I worked on two main software projects which are detailed under the cut.

Read the thesis <a href="{{ site.baseurl }}/documents/Joely_Nelson_Master_s_Thesis.pdf" target="_blank">here</a>

See thesis presentation slides <a href="{{ site.baseurl }}/documents/Joely Nelson Thesis Presentation.pdf" target="_blank">here</a>

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/ePIrc7szvMk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

<!-- more -->
The two softwatre projects I worked on are detailed below.

(1) Mock Data Generation Model for FACS-seq CRISPRa was a project where synthetic data was generated in the style of a CRISPRa experiment. In the experiment, effectiveness would be collected for several guides with the goal of using this data to uncover more rules for effective CRISPRa. The intent of the software project was to create this synthetic data to better understand and explore the data output by the experiment before real data could be produced. 

(2) *P. putida* RNA Seq Activation Filtering was a project where the goal was to find effective candidates for CRISPRa in *Pseudomonas putida*'s endogenous genome. This work was done by taking in several *P. putida* related datasets and using known CRISPRa rules to generate a list of suitable candidates for further study. The software filtered the list down to 9% of the original genes. Without taking into account the outputs of genome scale model,  ~9% of genes input into the software were considered suitable for CRISPRa. When taking into account the model outputs, the software produced 5 candidates for further experimentation. 

