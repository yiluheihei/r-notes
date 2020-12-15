# R packages and sources

**Useful packages, tutorials, and sources I collected. I will choose the one 
I think is best if multiple packages with similar functions.**

## packages

### base

- [rsrecovr](https://github.com/jmcphers/rsrecovr/tree/master/R), Recover 
  unsaved files from RStudio sessions

### models, statistics

- [corrr](https://github.com/tidymodels/corrr/), a package for exploring
  correlations in R. It focuses on creating and working with data frames of 
  correlations (instead of matrices) that can be easily explored via corrr 
  functions or by leveraging tools like those in the tidyverse.

### pipeline, reproducible research

- [drake](https://github.com/ropensci/drake), An R-focused pipeline toolkit for 
  reproducibility and high-performance computing
- [knitcitations](https://github.com/cboettig/knitcitations), Generate citations 
  for knitr markdown and html files.


### package development

- [devtools](https://github.com/r-lib/devtools), to make package development
  easier by providing R functions that simplify and expedite common tasks.
- [usethis](https://github.com/r-lib/usethis), automates repetitive tasks that
  arise during project setup and development, both for R packages and
  non-package projects.
- [biocthis](https://github.com/lcolladotor/biocthis), expands [usethis](https://github.com/r-lib/usethis) with 
  Bioconductor-friendly templates. These templates will help you quickly create
  an R package that either has Bioconductor dependencies or that you are
  thinking of submitting to Bioconductor one day.
- [BiocCheck](https://github.com/Bioconductor/BiocCheck), executes
  Bioconductor-specific package checks, encapsulates Bioconductor package
  guidelines and best practices, analyzing packages and reporting three
  categories of issues: ERROR, WARNING, and NOTE.
- [goodpractice](https://github.com/MangoTheCat/goodpractice), give advice about 
  good practices when building R packages. Advice includes functions and syntax 
  to avoid, package structure, code complexity, code formatting, etc.


### visualization

#### ggplot2 family

- [ggpointdensity](https://github.com/LKremer/ggpointdensity), 
  `geom_pointdensity()`: A cross between a scatter plot and a 2D density plot. 
  If you have lots of data points on top of each other, `geom_point()` fails to 
  give you an estimate of how many points are overlapping. `geom_density2d()` and
  geom_bin2d() solve this issue, but they make it impossible to investigate 
  individual outlier points, which may be of interest.
- [gghighlight](https://github.com/yutannihilation/gghighlight), highlight points and lines in ggplot2.
- [esquisse](https://github.com/dreamRs/esquisse), RStudio add-in to make plots
  with ggplot2. You can only create simple plots, you won't be able to use custom
  scales and all the power of ggplot2
- [ggtext](https://github.com/wilkelab/ggtext)， provides rich-text (basic HTML 
  and Markdown) support for ggplot2. Rich text can be used in plot annotations 
  (plot titles, subtitles, captions, axis labels, legends, etc.) 
- [gganimate](https://github.com/thomasp85/gganimate),  extends the grammar of 
  graphics as implemented by ggplot2 to include the description of animation.
- [ggthemes](https://github.com/jrnold/ggthemes), some extra geoms, scales, and 
  themes for ggplot.
- [hrbrthemes](https://github.com/hrbrmstr/hrbrthemes),  typography-centric 
  themes and theme components for ggplot2.
- [ggsci](https://github.com/nanxstats/ggsci), a collection of ggplot2 color 
  palettes inspired by scientific journals, data visualization libraries, science
  fiction movies, and TV shows.
- [ggstream](https://github.com/davidsjoberg/ggstream), is to create a simple 
  but powerful implementation of streamplot/streamgraph in ggplot2.
  
#### base plot family

- [ComplexHeatmap](https://github.com/jokergoo/ComplexHeatmap), provides a 
  highly flexible way to arrange multiple heatmaps and supports self-defined 
  annotation graphic(s.
- [ComplexUpset](https://github.com/krassowski/complex-upset/), offers a way to 
  generate UpSet plots with annotations.

#### javascript family 

- [highcharter](https://github.com/jbkunst/highcharter), Highcharter is a R
  wrapper for Highcharts javascript libray and its modules. Highcharts is very
  mature and flexible javascript charting library and it has a great and powerful
  API, See http://www.highcharts.com/demo.

  
### Bioinformatics

#### genomic

- [GenVisR](https://github.com/griffithlab/GenVisR/issues), package,
  visulization for genomic data
- [biomartr](https://github.com/ropensci/biomartr), genomic data retrieval with
  R

#### microbe/metagenomic

- [phyloseq](https://github.com/joey711/phyloseq), phyloseq: An R 
  Package for Reproducible Interactive Analysis and Graphics of Microbiome Census
  Data
- [microbiome](https://github.com/microbiome/microbiome), tools for
  microbiome analysis
- [MicrobiomeR](https://github.com/vallenderlab/MicrobiomeR), An R package for
  microbiome analysis that incorporates phyloseq, metacoder, taxa, and microbiome 
  in order to standardize and simplify common microbiome workflows
- [curatedMetagemicData](https://github.com/waldronlab/curatedMetagenomicData), 
  Curated and processed metagenomic data through ExperimentHub 
- [metacoder](https://github.com/grunwaldlab/metacoder), Parsing, Manipulation,
  and Visualization of Metabarcoding/Taxonomic data
- [microbiomeSeq](https://github.com/umerijaz/microbiomeSeq),  enhance the 
  available statistical analysis procedures in R by providing more analysis
  produre and visualisation of results for microbial communities data obtained
  from 16S rRNA
- [metavizR](https://github.com/epiviz/metavizr),  implements two-way
  communication between the R/Bioconductor environment and the metaviz web app
  for interactive visualization of microbiome sequencing result
- [metagenomeFeatures](https://github.com/HCBravoLab/metagenomeFeatures),
  exploring the taxonomic annotations for a marker-gene metagenomic sequence
  dataset. The package can be used to explore the taxonomic composition of a
  marker-gene database or annotated sequences from a marker-gene metagenome
  experiment
- [ShotgunFunctionalizedR](http://shotgun.math.chalmers.se/),  tools for
  importing, annotating and visualising metagenomic data produced by shotgun
  high-throughput sequencing. ShotgunFunctionalizeR contains several statistical
  procedures for assessing functional differences between samples, both for
  individual genes and for entire pathways. In addition to standard and
  previously published methods, we have developed and implemented a novel
  approach based on a Poisson model
- [melonnpan](https://github.com/biobakery/melonnpan), Model-based Genomically
  Informed High-dimensional Predictor of Microbial Community Metabolic Profiles
- [pavian](https://github.com/fbreitwieser/pavian), a interactive browser
  application for analyzing and visualization metagenomics classification results
  from classifiers such as Kraken, Centrifuge and MetaPhlAn. Pavian also provides
  an alignment viewer for validation of matches to a particular genome.
- [microbiomeViz](https://github.com/lch14forever/microbiomeViz), Visualize
  microbiome data with black magic ggtree, lefse visualization
- [PathoStat](https://github.com/mani2012/PathoStat), Statistical Microbiome
  Analysis on metagenomics results from sequencing data samples
- [SpiecEasi](https://github.com/zdk123/SpiecEasi), Sparse InversE Covariance
  estimation for Ecological Association and Statistical Inference
- [microbiomeutilities](https://github.com/microsud/microbiomeutilities), a
  wrapper tool using phyloseq and microbiome R packages. Apart for some simple
  scripts, this package has a single function generates a HTML report with
  preliminary QC, Alpha Diversity, Ordination and Composition analysis of OTU
  tables
- [Tax4Fun](http://tax4fun.gobics.de/), predicting functional profiles from
  metagenomic 16S rRNA data
- [taxize](https://github.com/ropensci/taxize), search over many taxonomic data
  sources for species names (scientific and common) and download up and
  downstream taxonomic hierarchical information - among other things
- [taxa](https://github.com/ropensci/taxa), taxonomic classes and functions to manipulate them
- [MetaLonDA](https://github.com/aametwally/MetaLonDA), a flexible R package for identifying time intervals of differentially abundant features in metagenomic longitudinal studies



## tutorials

### web

- [htmlwidgets for R](http://gallery.htmlwidgets.org/), htmlwidgets gallery for R

### look source code of R packages

- [lookup](https://github.com/jimhester/lookup), package, Lookup R full  
  function definitions, including compiled code, S3 and S4 methods.
- [Accessing R Source](https://github.com/jennybc/access-r-source), source of R
  function, S3 class and compiled code

### visualization

- [Accelerate your plots with ggforce](https://rviews.rstudio.com/2019/09/19/intro-to-ggforce/)

- [network visualization](https://kateto.net/network-visualization),  a 
  comprehensive tutorial on network visualization with R. It covers data input 
  and formats, visualization basics, parameters and layouts for one-mode and 
  bipartite graphs; dealing with multiplex links, interactive and animated 
  visualization for longitudinal networks; and visualizing networks on geographic
  maps.
- [A ggplot2 tutorial for beautiful ploting in R.](https://cedricscherer.netlify.app/2019/08/05/a-ggplot2-tutorial-for-beautiful-plotting-in-r/)
  
  
### data science

- [A graphical introducton to tidyr's `pivot_*()`](https://speakerdeck.com/yutannihilation/a-graphical-introduction-to-tidyrs-pivot-star), slide
- [A data.table and dplyr tour](https://atrebas.github.io/post/2019-03-03-datatable-dplyr/), tutorial

### bioinformatics

#### microbe/metagenomic

- [microbiome_helper](https://github.com/LangilleLab/microbiome_helper),some R
  scripts to help process and automate various microbiome and metagenomic
  bioinformatic tools, e.g. data2 output to R


## Awesome list

- [awesome-R](https://github.com/qinwf/awesome-R): A curated list of awesome R 
  packages and tools
- [awesome-ggplot2](https://github.com/erikgahner/awesome-ggplot2)
- [DataScienceR](https://github.com/ujjwalkarn/DataScienceR): a curated list of R
  tutorials for Data Science, NLP and Machine Learning

## ebook

Repository [R-ebook](https://github.com/yiluheihei/R-ebook) stored all the r programming e-books I collected.

## Contributing

Your contributions are always welcome!
