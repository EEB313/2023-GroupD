# 2023-GroupD

This is a hypothesis-driven project. We are testing the following hypotheses. 

1. The intensity of artificial light at night affects the frequency of bird-building collisions (alpha = 0.05). 
2. The frequency of bird-building collisions varies among species (alpha = 0.05).

Group work was divided by the following predictions. 

* Prediction 1a, the frequency of bird-building collisions increases with the intensity of artificial light: **Samina Hess**. 
* Prediction 2a, the frequency of bird-building collisions increases in species with lower wing maneuverability: **Yunhua Ren**. 
* Prediction 2b, the frequency of bird-building collisions is lower in omnivore species than in non-omnivore species: **Leslie Gao**. 

The contents of the group repository are as follows. 

**Data (raw and processed)**:

* Bird-building collision data from Winger et al. (Chicago_collision_data.csv).
  - Genus: genus of each lethal bird-building collision observed
  - Species: species of each collision observed
  - Date: date on which collision was observed, Y/M/D format
  - Locality: location where collision was observed(MP: McCormick Place convention centre and CHI: downtown Chicago)
* Collision data in wide format (Chicago_collision_data_wide.csv).
  - Species_Name: scientific name of each species
  - collision_freq: total number of collisions per species
* Light intensity data from Winger et al. (Light_levels_dryad.csv).
  - Date: date on which light intensity was quantified, Y/M/D format
  - Light_Score: measure of intensity of artificial light at night, values from 1 to 17
* Bird body mass and wingspan data from Avibase (Bird_Mass_Wingspan_Windload.csv).
  - Species_Name: scientific name of each species
  - Avg_Body_Mass_g: average body mass of each species in grams
  - Avg_Wingspan_cm: average wingspan of each species in centimeters
  - Wind_Load: wind load of each species, Avg_Body_Mass_g (g)/ Avg_Wingspan_cm (cm)
* Processed bird body mass and wingspan data (merged_data.csv).
  - Species_Name: scientific name of each species
  - Avg_Body_Mass_g: average body mass of each species in grams
  - Avg_Wingspan_cm: average wingspan of each species in centimeters
  - Wind_Load: wind load of each species, Avg_Body_Mass_g (g)/ Avg_Wingspan_cm (cm)
  - collision_freq: total collision frequencies per species
* Trophic level of each species from Avibase (trophic_level.csv).
  - x: scientific name of each species
  - trophic_level: trophic level of each species (Omnivore, Carnivore, Herbivore)

**Analyses**:

* Analyses for Prediction 1 (prediction_1.Rmd). 
* Analyses for Prediction 2a (2a_data_cleaning_merging.Rmd, prediction_2a.Rmd). 
* Analyses for Prediction 2b (prediction_2b.Rmd). 

**Other files**:

* This README.md file. 
* Project proposal (EEB313_Project_Proposal.pdf). 
* Mid-project update (Mid-project update.pdf). 
* Presentation slides(EEB313_Pre.pdf). 
* Project report (Final_project_report.pdf). 

