+++
title = "Research"
author = ["Gregory W. Schwartz"]
draft = false
+++

Chemotherapy and targeted drugs are effective treatments against cancer, **but
commonly lead to treatment-resistant cancer cells**. Cancer heterogeneity is known
to play a significant role in contributing towards this resistance. In order to
overcome treatment-resistance in cancer, our goal is to develop new
computational methods and algorithms to quantify and visualize cancer
heterogeneity to better understand the underlying mechanisms of resistance. To
accomplish this goal, we are creating new integrative tools at different scales
(such as between cancer subtypes or between individual cells within a single
cancer population) and data modalities (such as the transcriptome and the
epigenome) to guide therapy.

Some past examples of these initiatives as part of the [Faryabi Lab](https://faryabilab.com/) include:

<div class="clearfix">

<img src=/img/too-many-cells.svg class="pull-left" style="margin-right:5%;width:30%;height:auto" />

Single-cell analyses enable measurement of the transcriptome, chromatin
accessibility, and more at single-cell resolution. However, grouping similar
cells at different resolution cutoffs severely limits the exploration of both
common and rare heterogeneous populations. We have developed `TooManyCells`, a
suite of novel tools focused on simultaneous visualization of single-cell clade
relationships at all resolutions for single-cell RNA sequencing (scRNA-seq)
data.

</div>

<br></br>

<div class="clearfix">

<img src=/img/too-many-peaks-graphical-abstract.svg class="pull-left" style="margin-right:5%;width:30%;height:auto" />

While single-cell RNA sequencing can reveal much about the transcriptomic state
of individual cells, these states are largely set by the interaction of
transcription factors with regulatory elements within accessible chromatin
regions. To understand the relationship between cells with similar or unique
chromatin states, we developed `TooManyPeaks`, part of the `TooManyCells` suite,
for end-to-end analysis of single-cell assay for transposase-accessible
chromatin using sequencing (scATAC-seq) data.

</div>

<br></br>

<div class="clearfix">

<img src=/img/heatitup.svg class="pull-left" style="margin-right:5%;width:30%;height:auto" />

<div class="clearfix">
  <div></div>

Poor prognosis of patients with acute myeloid leukemia can be predicted based on
the presence of internal tandem duplications (ITDs) in Fms-like tyrosine kinase
3 (_FLT3_). We discovered new classes of _FLT3_-ITDs that predict patient
outcomes by creating `HeatITup`, an algorithm that identifies, characterizes,
and visualizes these classes of _FLT3_-ITDs.

</div>

</div>

<br></br>

<div class="clearfix">

<img src=/img/integreat.svg class="pull-left" style="margin-right:5%;width:30%;height:auto" />

While we can measure different modalities, such as the transcriptome and
proteome, it is difficult to analytically relate each level of information in a
systematic manner. We developed `inteGREAT`, an algorithm to use integration and
differential integration between conditions to identify biomarkers across
modalities.

</div>

<br></br>