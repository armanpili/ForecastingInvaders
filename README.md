# Quantitative Invasion Risk Assessment for Forecasting Pontential Invaders

## Research rationale
The ever-increasing and expanding globalisation of trade and transport underpins the escalating global problem of biological invasions. Developing biosecurity infrastructures is crucial to anticipate and prevent the transport and introduction of invasive alien species,  but robust and defensible forecasts of potential invaders, especially species worldwide with no invasion history, are rare. 

## The tool
Here, we aim to support decision-making by developing a quantitative invasion risk assessment tool based on invasion syndromes (i.e. attributes of a typical invasive alien species). We implemented a multiple imputation with chain equation workflow to estimate invasion syndromes from imputed datasets of species’ life-history and ecological traits (e.g., body size, reproductive traits, microhabitat) and macroecological patterns (e.g., geographic range size, commonness, habitat generalism, tolerance to disturbance). 

The tool is run under R computing program. And this repository contains the R scripts and sample files to run the tool.

The description and application of tool can be read in full in Pili et al. (XXXX).

## The repository

### There are four core R scripts.

1. macroeclogicalPatterns.Rmd --- for quantifying macroecological patterns.
2. PhylogeneticEigenvectorMapping.Rmd --- for mapping phylogenetic eigenvectors and determining optimal number of phylogenetic eigenvectors for phylogenetic imputation.
3. Multipleimputation.Rmd --- for multiple imputation of life-history and ecological traits and macroecological patterns.
4. invasionSyndromesModels.Rmd --- for modelling invasion syndromes.

### The file structure of your .Rproject

should ideally have:

* ./data/
* ./data/ecoregions/ # retrieve from source. See macroecologicalPatterns.Rmd
* ./data/habitats/ # retrieve from source. See macroecologicalPatterns.Rmd
* ./data/humanFootprint/ # retrieve from source. See macroecologicalPatterns.Rmd
* ./data/invasionHistory/ # provided
* ./data/occurrenceData/ # retrieve from source. See macroecologicalPatterns.Rmd
* ./data/phylogeneticTree/ # retrieve from source. See PhylogeneticEigenvectorMapping.Rmd
* ./data/ports/ # retrieve from source. See macroecologicalPatterns.Rmd
* /data/rangeMaps/ # retrieve from source. See macroecologicalPatterns.Rmd
* ./input/ #example data to run Multipleimputation.Rmd and invasionSyndromesModels.Rmd are included
* ./output/
* ./output/miceRangeError/
* ./output/miceRangeImp/
* ./output/miceRangeImportance/
* ./output/rf_fineTune/
* ./output/rf_pred/
* ./figures/


