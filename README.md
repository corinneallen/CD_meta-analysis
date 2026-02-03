This repository includes all data and code associated with the following manuscript:

# Co-occurrence patterns of photosymbiont genera in reef-building corals: a global review and meta-analysis

**Authors**: Corinne E. Allen, Eve C. Hinchliffe, David J. Suggett, Michael Kühl, Teina Rongo, Wing Yan Chan, Madeleine J.H. van Oppen, & Matthew R. Nitschke

**Journal**: Pending

**Link**: Pending

## Abstract

Coral reefs are experiencing unprecedented global declines driven by intensifying marine heatwaves, deoxygenation, and other consequences of climate change. One trait that may enhance coral resilience is their ability to harbour diverse communities of microalgal symbionts (Symbiodiniaceae). *Cladocopium* and *Durusdinium* are two common Symbiodiniaceae genera harbouring functionally different traits; however, the extent to which they co-occur within coral hosts has not yet been explored. Here, we conducted a systematic literature review and meta-analysis to assess global patterns of *Cladocopium*-*Durusdinium* co-occurrence and co-phylogeny, synthesising data from ~36,000 coral colonies across 378 studies, 98 coral genera, 77 countries and territories, 11 genetic markers, and 13 genetic analysis techniques. Co-occurrence prevalence across these studies was 9.6%, with estimates varying across methodological, biological, spatial, and study variables. Incorporation of more recent high-sensitivity genotyping and intra-colony sampling increased this estimate by up to 7.1-fold, suggesting that *Cladocopium*-*Durusdinium* co-occurrence may be more common than previously recognised. We also identified a co-phylogenetic signal between putative *Cladocopium* and *Durusdinium* taxa, suggesting that in some cases, these symbionts have co-evolved. Together, these findings contribute to the understanding of eco-evolutionary relationships between symbionts within coral hosts, providing important insight into the adaptive capacity of corals in a changing climate.


## Repository contents

### Data
* **data/symportal_datasets**: Downloaded SymPortal datasets for 41 articles (its2_type_profiles and post_med_seqs files included for each article)
* **data/symportal_metadata**: Downloaded SymPortal metadata files for 41 articles (its2_type_profiles and post_med_seqs files included for each article)
* **data/Table_S1**: List of articles returned from the literature search and their fates after the abstract/title screen and full text review
* **data/Table_S2**: Term library that was used to sort articles
* **data/Table_S3_database**: Full database
* **data/Table_S4**: Articles that used multiple methods or markers to analyse the same symbiont samples and the results from the staging teps to determine which method or marker was used in downstream analyses
* **data/Table_S5**: Recommended template for reporting symbiont data and associated metadata

### Analysis

* **analysis/CD_meta-analysis_code.Rmd**: includes all analyses within the manuscript, including:
  * Bibliographic analysis/article sorting
  * Database cleaning
  * Systematic review analyses (Part 1)
  * Meta-analysis (Part 2)
  * Coral phylogenetic analyses (Part 3)
  * *Cladocopium*-*Durusdinium* co-phylogeny analyses (Part 4)
  * Inspecting CD:D ratio as a function of relative abundance filtering threshold (Part 5)
* **analysis/all-best-tree-jan2021.raxml.support**: required for scleractinian coral phylogenetic analyses within the .Rmd file; obtained from Quek et al. (2023)
* **analysis/functions.R**: custom functions

### Outputs

* **outputs/merged_profs.csv**: merged profile data from all datasets downloaded from SymPortal
* **outputs/merged_data.csv**: merged metadata from all datasets downloaded from SymPortal
* **outputs/c_unidist.rds**: calculated UniFrac distances from *Cladocopium* profiles
* **outputs/d_unidist.rds**: calculated UniFrac distances from *Durusdinium* profiles
* **outputs/cd_cophy.rds** PACo results and permutation test for *Cladocopium*-*Durusdinium* phylogenetic congruence









