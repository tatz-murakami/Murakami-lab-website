---
title: Research
nav:
  order: 1
  tooltip: Our research
---

# {% include icon.html icon="fa-solid fa-flask-vial" %}Research

We aim to upgrade human neuroscience infrastructure to support modern technologies like spatial omics and 3D imaging.

{% include section.html %}

# {% include icon.html icon="fa-solid fa-microscope" %}Projects

## Three-Dimensional Transcriptomic Visualization

We develop and apply cutting-edge imaging methods to map gene expression in the mammalian brain with cellular resolution and anatomical precision. At the core of our work is mFISH3D, a technique we developed for three-dimensional in situ hybridization of mRNA in intact, cleared brain tissue. Unlike approaches that rely on genetically encoded reporters, mFISH3D enables direct visualization of endogenous gene expression, preserving the spatial context of native molecular signals.

By combining mFISH3D with light-sheet microscopy, we can detect and quantify multiple transcripts simultaneously across the whole brain, generating detailed maps of transcriptional activity. This approach allows us to study gene expression dynamics within intact neural circuits and across brain regions, providing insights into how molecular states are organized in space.

We apply mFISH3D to investigate how the brain’s gene expression landscape is shaped by development, experience, and disease. Our broader goal is to build comprehensive, spatially resolved molecular atlases that bridge single-cell gene expression with systems-level brain function.

## Deep Learning–Accelerated Image Analysis

Light-sheet microscopy of cleared tissue generates large, high-resolution volumetric datasets that are rich in biological information but challenging to analyze manually. We develop deep learning–based tools to automate the processing and interpretation of these complex images, enabling scalable and precise quantification of cellular and molecular features across the whole brain.

We design and train custom neural networks for key tasks such as 3D cell segmentation, transcript or protein signal detection, and anatomical alignment. These models are optimized for the unique characteristics of cleared tissue imaging, including variable contrast, dense labeling, and large field-of-view volumes.

Our computational workflows integrate deep learning with statistical analysis and interactive visualization, allowing us to detect spatial patterns, quantify changes across experimental conditions, and extract biological insights from massive datasets. By building flexible, generalizable pipelines, we aim to accelerate discovery from cleared-tissue imaging across a wide range of labeling strategies and biological questions.

## Comparative Neuroanatomy in Disease

To understand how disease impacts the human brain, it is essential to separate pathological changes from the natural anatomical variation that exists across individuals. We develop analysis techniques that enable comparisons across human brain samples while minimizing the influence of inter-individual differences in brain shape and size.

Rather than relying on spatial normalization or alignment, we focus on extracting biologically relevant features—such as morphogenic trajectory, cell density, molecular expression patterns, and cytoarchitectural organization—that can be quantified and compared within anatomically corresponding regions. By using region-aware statistical frameworks and population-level analysis, we aim to identify consistent disease-associated alterations that are robust to anatomical heterogeneity.

This strategy allows us to detect molecular and structural signatures of disease with high resolution, while preserving the inherent diversity of the human brain. Through this work, we aim to reveal how neurological and psychiatric disorders reshape brain architecture in reproducible and quantifiable ways.

{% include section.html %}
