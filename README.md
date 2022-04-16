# Data files and analysis scripts for the study "Pet dogs’ behavioural reaction to their caregiver’s interactions with a third party: join in or interrupt?"


## Structure 

```
.
  fake_dog_interaction_behavioral_data_markdown.rmd: R script of the GLMMs and plots of the behavioral data (Reaction phase)
  fake_dog_interaction_behavioral_ratings_markdown.rmd: R script of the ordinal regressions and plots of the behavioral ratings in the different experimental phases.
├──  graphics      <-- Data plots.
├──  data          <-- Data files.
                      dog_jealousy_aggregated_data.csv: : behavioral data in the reaction phases.
                      dog_jealousy_attitude_agg_data.csv: data of the behavioral ratings in the introduction and interaction phases.
                      dog_jealousy_attitude_reaction_phase_agg_data.csv: data of the behavioral ratings in the reaction phase.
├──  functions     <-- Functions for confidence interval bootstraps and model stability checks. Functions kindly provided by Roger Mundry.
```