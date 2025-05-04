# RemovalCH_Manuscript
This repository contains the full data processing and statistical analysis workflow for a study on invasive plant management across an elevational gradient in the Swiss Alps. It includes two R Markdown documents:

# 01_RemovalExperiment 
Analyzes species-specific recovery and community-level responses following the removal of three nonnative plant species (Erigeron annuus, Solidago canadensis, Lupinus polyphyllus) across multiple sites and years. The script imports and cleans vegetation cover data, transforms cover scores to numeric proportions, and fits generalized linear mixed models (GLMMs) with beta-distributed responses to assess the relationship of cover changes with several different predictors. Visual outputs include figures depicting cover changes in the focal species with predicted regression lines as well as changes in other cover groups recorded.

# 02_GerminationExperiment
Investigates germination patterns of Erigeron annuus and Solidago canadensis in relation to elevation, vegetation cover, and sampling area. This script processes field data from a seedling emergence experiment and uses negative binomial regression models to handle overdispersed count data. It includes model diagnostics and figures visualizing predicted germination responses to site-level predictors.

These scripts are part of the analysis for a manuscript submitted to Alpine Botany (May 2025) and are designed to ensure reproducibility of the results.
