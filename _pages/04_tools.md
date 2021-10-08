---
title: "Tools"
layout: "single"
permalink: "/04_tools/"
last_modified_at: 2021-04-09
toc: true
---


<p style="font-size:15px" align="justify">
Compilation of platforms and software for data analysis and scientific research.<br>
(ongoing work)
</p>

#### Platforms & environments
<p style="font-size:15px" align="justify">
These tools help gather several programs and/or major packages into one single pot; some are web-based. IDEs are good alternatives that combine a user-interface layout with powerful programs/programming languages.
</p>

General
<br><a style="font-size:15px" href="https://www.anaconda.com/">Anaconda</a>
<br><a style="font-size:15px" href="https://jupyter.org/">Jupyter Notebook</a>

R
<br><a style="font-size:15px" href="https://www.rstudio.com/">RStudio</a>
<br><a style="font-size:15px" href="https://rcompanion.org/handbook/">rcompanion: a whole bunch of things for R and data analysis</a>

#### Bioinformatics
galaxy.org
<p style="font-size:15px" align="justify">
<em>"Galaxy is an open, web-based platform for accessible, reproducible, and transparent computational research."</em> (taken from official  website) <a href="https://galaxyproject.org/">Galaxy</a>
</p>

genome browsers
<p style="font-size:15px" align="justify">
Genome browsers are online tools to help access various genetic information dynamically  and in a personalized way. There are multiple applications and tons of information accessible  there.
<br><a href="https://genome-euro.ucsc.edu/">University of California Santa Cruz (UCSC)</a>
<br><a href="https://www.ncbi.nlm.nih.gov/genome/gdv/">National Center for Biotechnology Information (NCBI)</a>
</p>

gene ontology
<p style="font-size:15px" align="justify">
Gene ontology terms are used to standardize and facilitate a common language in genetics. <em>"An ontology is a formal representation of a body of knowledge within a given domain. Ontologies usually consist of a set of classes (or terms or concepts) with relations that operate between them. The Gene Ontology (GO) describes our knowledge of the biological domain with respect to... molecular functions (MF), biological processes (BP) and cellular components (CP)..."</em> (taken from official  website) <a href="http://geneontology.org/">Gene Ontology - Unifying Biology</a>
</p>

<p style="font-size:15px" align="justify">
<br>A list of platforms to conduct gene-ontology and gene-network analysis
<br><a href="http://www-legacy.geneontology.org/GO.tools_by_type.browser.shtml">External list (website maybe not safe)</a>
<br><a href="http://www.pantherdb.org/">PANTHER</a>
<br><a href="https://string-db.org/">String</a>
<br><a href="https://david.ncifcrf.gov/">DAVID</a>

<br><a href="http://www.webgestalt.org">WebGestalt</a>: interactive web-tool that combine tools above
</p>

#### Software & packages
##### Management
openBIS
<p style="font-size:15px" align="justify">
Laboratory notebook and inventory manager. It help organize all sorts of information about experimental studies, particularly focused on laboratory studies. <a href="https://openbis.ch/">openBIS</a>
</p>

##### Workflows
snakemake
<p style="font-size:15px" align="justify">
<em>"The Snakemake workflow management system is a tool to create reproducible and scalable data analyses. Workflows are described via a human readable, Python based language. They can be seamlessly scaled to server, cluster, grid and cloud environments, without the need to modify the workflow definition. Finally, Snakemake workflows can entail a description of required software, which will be automatically deployed to any execution environment."</em> (taken from official  website) <a href="https://snakemake.readthedocs.io/en/stable/">snakemake</a>
</p>

workflowr
<p style="font-size:15px" align="justify">
<em>"The workflowr R package helps researchers organize their analyses in a way that promotes effective project management, reproducibility, collaboration, and sharing of results. Workflowr combines literate programming (knitr and rmarkdown) and version control (Git, via git2r) to generate a website containing time-stamped, versioned, and documented results. Any R user can quickly and easily adopt workflowr."</em> (taken from official  website) <a href="https://jdblischak.github.io/workflowr/">workflowr</a>
</p>

#### Epigenetics
##### software
<p style="font-size:15px" align="justify">
<a href="https://bioconductor.org/">Bioconductor</a> has a comprehensive list of packages related to epigenetic data analysis. See search results in their database <a href="https://bioconductor.org/help/search/index.html?q=epigenetics/">here</a>. Main examples:
<a href="https://pubmed.ncbi.nlm.nih.gov/24478339/">minfi</a>,
<a href="https://academic.oup.com/nar/article/43/7/e47/2414268">limma</a>,
<a href="https://academic.oup.com/bioinformatics/article/34/23/3983/5042224">meffil</a>,
<a href="https://rnbeads.org/index.html">RnBeads</a>,
<a href="https://academic.oup.com/bioinformatics/article/33/24/3982/4082274">ChAMP</a>,
<a href="https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2804-7">pwrEWAS</a>.
</p>

##### references
<p style="font-size:15px" align="justify">
Comprehensive information is gathered in <a href="https://epigenie.com/epigenetic-tools-and-databases/">epigenie</a>.
</p>

#### Literature search
connected papers
<p style="font-size:15px" align="justify">
Give a specific paper and see what it comes out of it in terms of publication citations and connections between papers. Appealing visual and intuitive tool for literature reviews. <a href="https://www.connectedpapers.com/">Connected Papers</a>
</p>

doc<em>ear</em>
<p style="font-size:15px" align="justify">
This is a neat tool for mind mapping and organization. <em>Docear is a unique solution to academic literature management, i.e. it helps you organizing, creating, and discovering academic literature.</em> (taken from official  website) <a href="https://docear.com/">Doc<em>ear</em></a>
</p>

#### Scientific writing
rrtools
<p style="font-size:15px" align="justify">
Tools for writing reproducible research in R. <em>"The goal of rrtools is to provide instructions, templates, and functions for making a basic compendium suitable for writing a reproducible journal article or report with R. This package documents the key steps and provides convenient functions for quickly creating a new research compendium. The approach is based generally on Kitzes et al. (2017), and more specifically on Marwick (2017), Marwick et al. (2018), and Wickham’s (2017) work using the R package structure as the basis for a research compendium."</em> (taken from official website). <a href="https://github.com/benmarwick/rrtools">rrtools</a>
</p>

rticles
<p style="font-size:15px" align="justify">
LaTeX-formatted templates for scientific articles to be written in R. <em>"The rticles package provides a suite of custom R Markdown LaTeX formats and templates for various formats. Most of the templates are provided and maintained by the community, and anyone can contribute a new template."</em> (taken from official website). <a href="https://cran.r-project.org/web/packages/rticles/index.html">rticles</a>
</p>

#### Randomization
minimpy
<p style="font-size:15px" align="justify">
JAVA application used for parallel randomization of experimental designs. <em>"A desktop application program for sequential allocation of subjects to treatment groups in clinical trials by using the method of minimization"</em> (taken from official website). <a href="https://sourceforge.net/projects/minimpy/#">MinimPy</a>
</p>

R packages
<p style="font-size:15px" align="justify">
See <a href="https://cran.r-project.org/web/packages/randomizeR/index.html">randomizeR</a> and <a href="https://cran.r-project.org/web/packages/randomizr/">randomizr</a>
</p>
