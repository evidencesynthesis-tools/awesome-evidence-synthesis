# Awesome Evidence Synthesis Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Systematic methods for identifying, evaluating, and synthesizing research evidence across multiple studies.

Systematic methods for identifying, evaluating, and integrating research evidence across studies, with additional resources available at [evidencesynthesis-tools.github.io](https://evidencesynthesis-tools.github.io).

<a href="https://evidencesynthesis-tools.github.io"><img src="assets/banner4.png" width="800" alt="Evidence Synthesis Tools Banner"></a>

## Contents

- [Literature Search](#literature-search)
- [Text Mining & NLP](#text-mining--nlp)
- [Screening](#screening)
- [Data Extraction & Cleaning](#data-extraction--cleaning)
- [Risk of Bias Assessment](#risk-of-bias-assessment)
- [Reference Management](#reference-management)
- [Workflow & Automation](#workflow--automation)
- [Visualization & Reporting](#visualization--reporting)
- [Meta-analysis](#meta-analysis)
- [Statistics](#statistics)


## Literature Search

- [CitationChaser](https://estech.shinyapps.io/citationchaser/) - Automates backward and forward citation chasing using Lens.org API to find cited and citing papers for systematic reviews.
- [litsearchr](https://elizagrames.github.io/litsearchr/) - An R package and Shiny app that uses text mining to identify important search terms, builds Boolean strings across databases, and test search performance.
- [OpenAlex](https://openalex.org/) - A fully open catalog of the global research system providing an API to retrieve millions of works, authors, and concepts for searching.
- [Systematic Review Accelerator 2](https://github.com/IEBH/SRA2) - The core Systematic Review Accelerator (SRA) application, a key open-source platform for evidence synthesis.
- [TERA Explorer](https://github.com/IEBH/TERA-explorer) - A simple TERA project viewer and editor, confirming "TERA" as an active project name within the suite.
- [SRA Polyglot](https://iebh.github.io/sra-polyglot/) - A tool to convert between different medical database search formats, directly relevant to search strategy development.
- [BioEntrez](https://biopython.org/) - A module within the Biopython library that provides a programmatic interface to the NCBI Entrez utilities for automated searches and data retrieval.
- [Entrez Direct](https://www.ncbi.nlm.nih.gov/books/NBK179288/) - A set of command-line utilities for accessing the NCBI Entrez databases, allowing for powerful, scriptable PubMed searches.
- [Rentrez](https://docs.ropensci.org/rentrez/) - An R package providing an R interface to the NCBI E-utilities API for searching PubMed, downloading records, and fetching linked data programmatically.
- [Carrot2](https://carrot2.org/) - An open-source search results clustering engine that automatically organizes search results into thematic categories to help researchers refine search queries.
- [PyMedTermino](https://pypi.org/project/PyMedTermino/) - A Python library designed to manipulate the MeSH (Medical Subject Headings) thesaurus for biomedical search strategies and programmatic search string creation.
- [Paperfetcher](https://paperfetcher.github.io) - Automates handsearching and citation searching for systematic reviews using Crossref and COCI databases, enabling one-click snowballing and RIS exports.
- [PubMed Search Tester](https://esperr.github.io/pubmed-search-tester/about.html) - A web-based tool designed to help librarians and researchers construct and validate PubMed search queries in real-time.
- [europepmc](https://docs.ropensci.org/europepmc/) - An R package to retrieve metadata and full text from the Europe PMC database, a crucial resource for accessing biomedical literature and open-access content.
- [rcrossref](https://docs.ropensci.org/rcrossref/) - An open-source R client for interacting with the Crossref REST API to retrieve scholarly metadata, DOI records, and citation information.
- [citracer](https://github.com/marcpinet/citracer) - Trace citation chains for any concept across research papers and render them as an interactive graph.

## Text Mining & NLP

- [PubTator 3.0](https://www.ncbi.nlm.nih.gov/research/pubtator3/) - A web-based semantic annotation system for biomedical literature, automatically recognizing concepts like genes, diseases, and chemicals.
- [BioTextQuest v2.0](https://bioinformatics.med.uoc.gr/shinyapps/app/biotextquest) - An open-source web portal for biomedical literature mining that clusters PubMed search results to facilitate concept discovery and entity association.
- [Kindred](https://kindred.readthedocs.io/en/stable/) - A Python library for supervised relation extraction from biomedical text, identifying structured relationships (e.g., gene-disease) using machine learning.
- [LitLLMs](https://litllm.github.io) - An open-source framework for applying large language models to literature review tasks, including summarization, retrieval, and synthesis.
- [QuickUMLS](https://pypi.org/project/medspacy-quickumls/) - A fast, unsupervised approach for extracting concepts from biomedical text and mapping them to UMLS concepts, significantly faster than MetaMap.
- [MetaNLP](https://cran.r-project.org/package=MetaNLP) - Natural language processing for meta-analysis, processing titles and abstracts for data extraction and synthesis.

## Screening

- [ASReview](https://asreview.ai/) - An open-source machine learning tool for systematic reviews that assists researchers in screening papers interactively and efficiently.
- [ReviewAid](https://reviewaid.github.io) - An open-source AI full text screening & data extraction assistant designed to speed up systematic review process.
- [Abstrackr](https://abstrackr.com) - A free, open-source web application designed to help researchers screen citations for systematic reviews using machine learning.
- [revtools](https://cran.r-project.org/web/packages/revtools/) - A toolkit for systematic reviews in R, facilitating article screening via visual inspection and topic modeling of search results.
- [metagear](https://cran.r-project.org/web/packages/metagear/) - R package that provides tools for article deduplication, downloading PDFs, and interactive screening.
- [RobotSearch](https://www.robotreviewer.net/blog/2018/10/2/robotsearch-is-online-apply-our-classifier-to-your-search-results) - A machine learning tool designed to filter out articles that do not describe randomized controlled trials (RCTs) from search results.
- [DenseReviewer](https://densereviewer.ielab.io) - A Python-based tool designed to accelerate the screening phase by using Dense Retrieval models to rank relevant studies and incorporating active learning.
- [rayyanR](https://github.com/befriendabacterium/rayyanR) - An R package designed to process screening decisions exported from the Rayyan systematic review platform, structuring them for analysis and Prisma flow diagrams.

## Data Extraction & Cleaning

- [WebPlotDigitizer (v4)](https://apps.automeris.io/wpd/) - An open-source, semi-automated tool to extract numeric data from plot images, useful for extracting data from graphs for meta-analysis.
- [ImageJ](https://imagej.net/ij/) - A Java-based image processing program widely used to extract data points from raster plots and images.
- [Engauge Digitizer](https://akhuettel.github.io/engauge-digitizer/) - Open source software for converting image files back to numbers, extracting data from graph images for analysis.
- [Recogito](https://recogito.pelagios.org/) - An open-source web-based tool for collaborative document annotation and text mapping.
- [metaDigitise](https://cran.r-project.org/web/packages/metaDigitise/index.html) - An R package for high-throughput, reproducible extraction of data from published figures to digitize plots efficiently.
- [SurvdigitizeR](https://pechlilab.shinyapps.io/SurvdigitizeR/) - An R package and Shiny application algorithm for automated survival curve digitization with accuracy comparable to manual methods.
- [Taguette](https://www.taguette.org/) - An open-source qualitative analysis tool that supports code-and-retrieval methods using simple text files for qualitative data extraction.
- [QualCoder](https://qualcoder.wordpress.com) - A fully open-source qualitative analysis tool for text, audio, video, and images, providing advanced coding and analysis features.
- [MSE FINDR](https://apsjournals.apsnet.org/doi/10.1094/PDIS-11-23-2519-SR) - A Shiny R application to estimate Mean Square Error using treatment means and post hoc test results.
- [Auto-STEED](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0311358) - A data mining tool for automated extraction of experimental parameters and risk of bias items from in vivo publications.
- [LitOrganizer](https://www.sciencedirect.com/science/article/pii/S2352711025001657) - Automates the process of data extraction and organization for scientific literature reviews, running locally as a management tool.
- [prismAId](https://prismaid.review) - An open-source toolkit designed to support systematic literature reviews using generative AI for structured information extraction.
- [ReAct-ExtrAct](https://react-extract.streamlit.app) - An open-source tool for automated, source-grounded data extraction in systematic reviews.

## Risk of Bias Assessment

- [RobotReviewer](https://www.robotreviewer.net) - An open-source system that automates risk-of-bias assessment and data extraction for randomized controlled trials using NLP.
- [Critiplot](https://critiplot.vercel.app) - A specialized open-source tool for generating traffic light plots for MMAT, ROBIS, GRADE, NOS, JBI Case Series/report assessments.
- [robvis](https://www.riskofbias.info/welcome/robvis-visualization-tool) - An R package and web app for generating risk-of-bias assessment plots, supporting RoB2, ROBINS-I, QUADAS-2, and more.
- [NOS-TLPlot](https://nos-tlplot.vercel.app) - Open-source tool designed to visualize Newcastle-Ottawa Scale (NOS) assessments using traffic light plots.
- [psychometric](https://cran.r-project.org/web/packages/psychometric/) - R package for applied psychometric theory, offering functions for reliability analysis, validity, and item analysis.
- [CINeMA](https://cinema.ispm.unibe.ch/) - Software for semiautomated assessment of the confidence in the results of network meta-analysis, guiding users through the evaluation process.

## Reference Management

- [Zotero](https://www.zotero.org/) - Free, open-source reference manager that helps collect, organize, cite, and share research sources.
- [JabRef](https://www.jabref.org/) - Open-source bibliography reference manager. The native file format used is BibTeX, standard for LaTeX.
- [OpenRefine](https://openrefine.org/) - A power tool for working with messy data, cleaning it, transforming it, and extending it with web services.
- [Dedupe](https://docs.dedupe.io/en/latest/) - A Python library for fast, scalable fuzzy matching and deduplication of records (e.g., citations).
- [ASySD](https://camaradesuk.github.io/ASySD/) - A web application designed to de-duplicate large search results from multiple databases for systematic reviews efficiently.
- [HAWC](https://hawcproject.org/) - An open-source content management system used to guarantee transparency in systematic reviews, managing the review process and documentation.

## Workflow & Automation

- [Pandoc](https://pandoc.org/) - A universal document converter that turns files from one markup format into another (e.g., Word to Markdown), useful for document preparation.
- [OSF (Open Science Framework)](https://osf.io/) - An open-source project management tool supporting the full research lifecycle, from preregistration to data sharing and collaboration.
- [Markdown](https://rmarkdown.rstudio.com/) - A framework for creating dynamic documents that turn analysis code into fully reproducible reports for transparent documentation.
- [bookdown](https://bookdown.org/) - An R package that allows authors to write books and long-form reports using R Markdown to facilitate comprehensive systematic reviews.
- [SyRF](https://syrf.org.uk/) - The CAMARADES Systematic Review Facility (SyRF) is an open-source platform designed specifically for preclinical systematic reviews.
- [Prisma 2020 (Flow Diagram)](https://estech.shinyapps.io/PRISMA_flowdiagram_latest/) - The official Prisma 2020 Flow Diagram Generator (Shiny App & R package) automatically creates a correctly formatted Prisma flow diagram.
- [ROSES flowchart](https://estech.shinyapps.io/roses_flowchart/) - An R package and Shiny app for creating flow diagrams compliant with the ROSES (Reporting Standards for Systematic Evidence Syntheses) guidelines.
- [PROMETHEUS](https://github.com/joaopftorres/PROMETHEUS) - A human-centered pipeline designed to streamline Systematic Literature Reviews using Large Language Models, operating locally to support researchers.
- [LLAssist](https://arxiv.org/abs/2407.13993) - Provides simple tools for automating literature reviews by leveraging Large Language Models and Natural Language Processing to extract information and evaluate relevance.
- [ProfOlaf](https://arxiv.org/abs/2510.26750v2) - An open-source semi-automated tool designed to support systematic literature reviews by assisting in study selection and organization. 
- [LatteReview](https://pouriarouzrokh.github.io/LatteReview/) - An open-source multi-agent framework designed to automate systematic review workflows using large language models.
- [EvidenceSynthesis](https://ohdsi.github.io/EvidenceSynthesis/) - Contains routines for combining causal effect estimates and study diagnostics across multiple data sites in a distributed study using meta-analysis.

## Visualization & Reporting

- [VOSviewer](https://www.vosviewer.com/) - A software tool for constructing and visualizing bibliometric networks, useful for evidence mapping and co-citation analysis.
- [EviAtlas](https://estech.shinyapps.io/eviatlas/) - A tool for creating systematic map visualizations to organize and display the distribution of evidence in a specific field.
- [bibliometrix](http://www.bibliometrix.org/) - A comprehensive tool for quantitative research in bibliometrics and scientometrics, providing all the main tools for bibliometric analysis.
- [Gephi](https://gephi.org/) - An open-source platform for visualizing and exploring large networks and graphs, widely used for network analysis and science mapping.
- [Cytoscape](https://cytoscape.org/) - An open source software platform for visualizing complex networks and integrating these with any type of attribute data.
- [forestplot](https://cran.r-project.org/web/packages/forestplot/) - An R package specifically designed for creating forest plots, which are standard visualizations in meta-analysis.
- [MAvis](http://kylehamilton.net/shiny/MAVIS/) - An interactive Shiny application designed for visualizing meta-analysis data, including forest plots, funnel plots, and L'Abbe plots.
- [metaviz](https://cloud.r-project.org/web/packages/metaviz/vignettes/metaviz.html) - An R package for creating flexible visualizations for meta-analytic data, including rainforest plots and subgroup visualizations.
- [ShinyMeta](https://rstudio.github.io/shinymeta/) - A Shiny web application that provides a graphical user interface for performing meta-analysis and meta-regression using the 'metafor' package.
- [Kilim Plot / Vitruvian Plot](https://cinema.ispm.unibe.ch/shinies/kilim/) - A graphical tool for visualizing network meta-analysis results for multiple outcomes, compactly summarizing absolute treatment effects.
- [MetaAnalyser](https://cran.r-project.org/package=MetaAnalyser) - An interactive application to visualize meta-analysis data as a physical weighing machine.
- [viscomp](https://cran.r-project.org/package=viscomp) - Visualization tools for exploring multi-component interventions in network meta-analysis.
- [nmaplateplot](https://cran.r-project.org/package=nmaplateplot) - The plate plot for network meta-analysis, a graphical display of treatment effects.
- [NMAforest](https://cran.r-project.org/web/packages/NMAforest/) - Provides customized forest plots for network meta-analysis, visualizing direct, indirect, and NMA effects.
- [Open Knowledge Maps](https://openknowledgemaps.org/) - An open-source visual discovery tool that creates a "knowledge map" of a research topic by clustering top papers.
- [CorTexT Manager](https://www.cortext.net) - A platform for analyzing and visualizing large textual corpora, particularly strong in bibliometric analysis and network visualization.

## Meta-analysis

- [metafor](https://www.metafor-project.org/) - A comprehensive R package for conducting meta-analyses, providing functions for fixed, random, and mixed-effects models.
- [meta](https://cran.r-project.org/web/packages/meta/) - A user-friendly R package for standard meta-analysis in clinical research, supporting binary, continuous, and diagnostic test accuracy data.
- [netmeta](https://cran.r-project.org/web/packages/netmeta/) - An R package for frequentist network meta-analysis using a graph-theoretical approach to estimate treatment effects.
- [OpenMEE](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12708) - An open-source, cross-platform software for meta-analysis in ecology and evolution, utilizing a graphical interface backed by 'metafor'.
- [OpenMetaAnalyst](https://www.jstatsoft.org/article/view/v049i05) - A user-friendly, open-source software for performing meta-analysis and meta-regression using a graphical interface.
- [JASP](https://jasp-stats.org/) - Free and open-source software for statistical analysis, featuring a graphical interface with a dedicated module for conducting meta-analysis.
- [OpenEpi](https://www.openepi.com/) - A web-based, open-source set of epidemiologic calculators for statistics in descriptive and analytic studies, useful for data extraction and statistical verification.
- [PyMC](https://www.pymc.io/) - A Python library for Bayesian statistical modeling and probabilistic machine learning focusing on Markov chain Monte Carlo (MCMC) algorithms.
- [JAGS](https://mcmc-jags.sourceforge.io) - A program for analysis of Bayesian hierarchical models using Markov Chain Monte Carlo (MCMC) simulation.
- [Stan](https://mc-stan.org/) - A state-of-the-art platform for statistical modeling and high-performance computation using Hamiltonian Monte Carlo (HMC).
- [meta4diag](https://cran.r-project.org/web/packages/meta4diag/) - An R package specifically designed for the Bayesian meta-analysis of diagnostic test accuracy studies handling complex data structures.
- [mada](https://cran.r-project.org/web/packages/mada/) - An R package that provides functions for the meta-analysis of diagnostic accuracy data, supporting various statistical models and visualization.
- [metaSEM](https://cran.r-project.org/web/packages/metaSEM/) - An R package for conducting meta-analytic structural equation modeling (MASEM) to synthesize correlation or covariance matrices across studies.
- [gemtc](https://cran.r-project.org/web/packages/gemtc/) - An R package for network meta-analysis using a Bayesian graphical model framework, primarily interfacing with JAGS.
- [multinma](https://cran.r-project.org/web/packages/multinma/) - An R package for network meta-analysis of randomized trials and observational studies, utilizing Stan for Bayesian inference.
- [dosresmeta](https://cran.r-project.org/web/packages/dosresmeta/) - An R package for performing dose-response meta-analysis of aggregated data using a one-stage approach to model non-linear relationships.
- [MetaForest](https://cran.r-project.org/web/packages/metaforest/index.html) - An R package that applies Random Forests to meta-analytic data to explore heterogeneity and model complex, non-linear relationships.
- [Bayesmeta](https://cran.r-project.org/web/packages/bayesmeta/) - An R package for conducting Bayesian random-effects meta-analysis with a focus on robust parameter estimation and predictive inference.
- [metaumbrella](https://metaumbrella.org) - An R package specifically designed to perform "Umbrella Reviews," which are systematic reviews of multiple meta-analyses.
- [robumeta](https://cran.r-project.org/web/packages/robumeta/) - An R package for conducting robust variance estimation (RVE) in meta-analysis, which is essential for handling dependent effect sizes.
- [dmetar](https://dmetar.protectlab.org) - A comprehensive R package to assist in conducting meta-analyses, providing helper functions for data preparation, effect size calculation, and bias assessment.
- [compute.es](https://cran.r-project.org/web/packages/compute.es/) - R package for computing effect sizes (d, g, r, log odds ratio) and their variances from various test statistics.
- [clubSandwich](https://cran.r-project.org/web/packages/clubSandwich/) - An R package providing cluster-robust variance estimators for models involving dependent effect sizes, such as multilevel or network meta-analysis.
- [MetaInsight](https://crsu.shinyapps.io/MetaInsight/) - A web-based tool that conducts network meta-analysis (NMA) via the web, providing an intuitive interface and interactive visualizations.
- [PyMARE](https://pymare.readthedocs.io/) - A Python library designed to perform meta-analysis tasks, including combining effect measures, heterogeneity testing, and generating forest plots.
- [Jamovi](https://www.jamovi.org/) - A free, open-source statistical spreadsheet designed to be easy to use, including modules for meta-analysis.
- [Meta-DiSc](http://www.metadisc.es/) - A free software tool used for the meta-analysis of diagnostic test accuracy studies, allowing users to perform statistical analyses and visualize results.
- [MetaDTA](https://crsu-metadta.le.ac.uk/MetaDTA/) - A web-based interactive tool for performing meta-analysis of diagnostic test accuracy studies that simplifies the implementation of complex bivariate hierarchical models.
- [DiagMeta](https://cran.r-project.org/web/packages/diagmeta/) - An R package used for the meta-analysis of diagnostic accuracy studies where multiple thresholds are reported, estimating the summary ROC curve.
- [HSROC](https://cran.r-project.org/src/contrib/Archive/HSROC/) - An R package that implements the Hierarchical Summary ROC model for diagnostic test accuracy meta-analysis within a Bayesian framework.
- [bamdit](https://cran.r-project.org/package=bamdit) - An R package for Bayesian meta-analysis of diagnostic test data that simplifies the implementation of hierarchical models using JAGS.
- [MBNMAdose](https://CRAN.r-project.org/package=MBNMAdose) - An R package for Model-Based Network Meta-Analysis (MBNMA) that integrates complex dose-response information into a single cohesive framework.
- [baggr](https://cran.r-project.org/package=baggr) - Bayesian meta-analysis of aggregated data using Stan, supporting various models including hierarchical and potential outcomes.
- [metaBMA](https://cran.r-project.org/package=metaBMA) - Bayesian model averaging for random and fixed effects meta-analysis, allowing for the comparison of different meta-analytic models.
- [metasens](https://cran.r-project.org/package=metasens) - Statistical methods for sensitivity analysis in meta-analysis, evaluating how sensitive results are to publication bias.
- [bipd](https://cran.r-project.org/package=bipd) - Bayesian Individual Patient Data Meta-Analysis using 'JAGS', facilitating the synthesis of IPD in a Bayesian framework.
- [RoBMA](https://fbartos.github.io/RoBMA/) - Robust Bayesian meta-analysis using model-averaging to adjust for publication bias.
- [metapsyTools](https://tools.metapsy.org) - Provides tools for preparing and analyzing meta-analytic datasets from the Metapsy psychotherapy databases, supporting effect size calculation and automated reporting.

## Statistics

- [statcheck](https://cran.r-project.org/web/packages/statcheck/index.html) - An R package that extracts statistical results from text and checks whether reported p-values are consistent with test statistics and degrees of freedom.
- [ArviZ](https://python.arviz.org/) - A Python library for exploratory analysis of Bayesian models, providing backend-agnostic plotting and diagnostics for Bayesian meta-analyses.
- [metacp](https://link.springer.com/article/10.1186/s12859-025-06126-z) - A versatile software package that implements statistical methods for the combination of both independent p-values and dependent p-values.
- [meta-maive](https://cran.r-project.org/package=MAIVE) - Meta-analysis instrumental variable estimator, addressing spurious precision in meta-analysis of observational research.
- [artma](https://cran.r-project.org/package=artma) - Automatic replication tools for meta-analysis, facilitating the reproduction of meta-analytic findings.
- [dmetatools](https://cran.r-project.org/package=dmetatools) - Computational tools for meta-analysis of diagnostic test accuracy studies, handling non-standard metrics.
- [wildmeta](https://cran.r-project.org/package=wildmeta) - Cluster wild bootstrapping for meta-analysis, providing hypothesis testing methods for dependent effect sizes.
- [mars](https://cran.r-project.org/package=mars) - Meta analysis and research synthesis tools for univariate and multivariate meta-analysis.
- [PINMA](https://cran.r-project.org/package=PINMA) - Improved methods to construct prediction intervals for network meta-analysis.
- [NMADTA](https://cran.r-project.org/package=NMADTA) - Network meta-analysis of multiple diagnostic test accuracy studies (1-5 tests) with missing data.
- [coefa](https://cran.r-project.org/package=coefa) - Meta analysis of factor analysis based on co-occurrence matrices.
- [appraise](https://cran.r-project.org/package=appraise) - Bias-aware evidence synthesis in systematic reviews, implementing a bias-aware framework.

## Contributing  <img src="assets/icon.png" width="90" align="right" />

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to suggest additions or changes.

## Footnotes

### Criteria & Policies
**Inclusion Criteria:** Tools must use a recognized open-source license (e.g., MIT, GPL), have a public code repository, be non-proprietary, be reusable/extensible, and be relevant to evidence synthesis.

**External API Policy:** Tools interacting with external APIs are included if they use an OSI-approved license, have public code, use external services only for data access/integration, and do not rely on hidden proprietary logic.
