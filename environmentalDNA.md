---
layout: article
title: What is environmental DNA?
header:
  theme: dark
  background: rgba(0, 0, 0, .35)
key: page-eDNA
---


Environmental DNA (eDNA) is DNA collected from the environment, such as water or soil, to determine which organisms have recently been in the sampling location. All organisms (both plants and animals) shed DNA naturally in the form of cells and DNA fragments, and by collecting the water or soil that contains the shed DNA, the presence of organisms can be determined without collecting the organisms themselves. 

![eDNAVisual](/assets/images/OceaneDNA.png)

## Steps to conduct an eDNA experiment

![eDNASteps2](/assets/images/eDNASteps2.jpg)

### Collection

The first step to any experiment is to collect your sample. Since the concept behind eDNA is that you can identify the presence of organisms by analyzing the DNA present in the water, collecting your sample simply involves collecting water. This can be done in a variety of ways - folks have done so by using a bucket attached to a stick, dropping a pail into a lake, using a Niskin bottle, or even an autonomous underwater vehicle. The way we collect water in this experiment (and a very common method in the marine sciences) is by using a Niskin bottle. To learn more about Niskin bottles, we invite you to walk through the experiment! Upon collecting water, it is important to then store the water in the dark and at a cold temperature to prevent your important DNA samples from breaking down before you have a chance to analyze them.

### Filtering

Filtering is the next step in all eDNA sampling protocols. Filtering your water through a filter with an extremely small mesh size (0.22 micrometer pores!) allows you to trap the DNA fragments and cells containing DNA on the filter. Researchers may use different filtering systems (for instance, a peristaltic pump versus a vacuum filter), but no matter the system, they all have the same function. At the end of this step, anything small floating in your water sample is now trapped on your filter, which will be stored in the freezer until you extract the DNA off of the filter. 

### Extraction

Extraction is the process of removing the DNA from the filter. On your filter you may have DNA as well as other materials such as proteins or cell organelles. However, to analyze your sample, you only want the DNA that is present on your filter. DNA extraction methods not only remove the DNA from your filter, but also remove those unwanted items (such as proteins) from your sample. There are many methods by which you can perform an eDNA extraction, though common ones include using a phenol-chloroform method or a pre-defined kit from a biotechnology company. At the end of this step, you should have a small tube with about 100 microliters of buffer containing your DNA.

### Amplification

Whether you are looking for one specific species in your sample or are interested in as many species as possible, amplification through polymerase chain reaction (PCR) is the next vital step of your experiment. PCR allows you to amplify a short fragment (usually around 200-500 basepairs) of DNA. PCR cycles through temperatures to allow for exponential amplification of your region of choice. At the end of the PCR step, you will have a small tube with about 20-50 microliters of sample that is mostly the one fragment of interest. Often, if you are interested in one specific organism, you may perform quantitative PCR (qPCR), which allows you to visualize and quantify the amount of that particular gene in your sample during each PCR cycle. This is then the final step of your experiment - as you can back-calculate the amount of organism in your environment based on the amount of that gene in your sample. If you are interested in multiple species, you may perform a normal (non-quantitative) PCR, then prepare the sample for further quantification analysis through sequencing.

### Sequencing & Analysis

If you are interested in examining multiple species in your eDNA sample, you will most likely perform what is called metabarcoding. This is the idea that your amplified DNA from your PCR can come from 2 or more organisms, and you want to determine what organisms they are. After amplifying your sample through PCR, you will then prepare it and send it off to a facility to be sequenced. The facility will return a (vary large) file to you that has the sequences (ATGCGTCA...) of each amplified fragment in your sample. From there, you would then perform computational analysis that will transform that raw data into information regarding which sequence correlates to which organism in your sample, as well as how many copies of that organism's DNA was presence in your sample.


