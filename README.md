This repo contains the scripts and Pili et al.(XXXX) files for quantifying the invasion risk of species worldwide, and forecasting potential invaders.

This is done under R platform.

Description of statistical workflow can be found in Pili et al. (XXXX).

There are four core R scripts.

1. macroeclogicalPatterns.Rmd --- for quantifying macroecological patterns.
2. PhylogeneticEigenvectorMapping.Rmd --- for mapping phylogenetic eigenvectors and determining optimal number of phylogenetic eigenvectors for phylogenetic imputation.
3. Multipleimputation.Rmd --- for multiple imputation of life-history and ecological traits and macroecological patterns.
4. invasionSyndromesModels.Rmd --- for modelling invasion syndromes.

The file structure of your .Rproject should ideally have:

./data/
./data/ecoregions/ # retrieve from source. See macroecologicalPatterns.Rmd
./data/habitats/ # retrieve from source. See macroecologicalPatterns.Rmd
./data/humanFootprint/ # retrieve from source. See macroecologicalPatterns.Rmd
./data/invasionHistory/ # provided
./data/occurrenceData/ # retrieve from source. See macroecologicalPatterns.Rmd
./data/phylogeneticTree/ # retrieve from source. See PhylogeneticEigenvectorMapping.Rmd
./data/ports/ # retrieve from source. See macroecologicalPatterns.Rmd
/data/rangeMaps/ # retrieve from source. See macroecologicalPatterns.Rmd

./input/ #example data to run Multipleimputation.Rmd and invasionSyndromesModels.Rmd are included

./output/
./output/miceRangeError/
./output/miceRangeImp/
./output/miceRangeImportance/
./output/rf_fineTune/
./output/rf_pred/

./figures/


